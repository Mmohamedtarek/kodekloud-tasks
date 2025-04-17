# Clone Git Repository to Storage Server

## Description
This task was completed as part of a hands-on DevOps lab on KodeKloud. The goal was to clone an official Git repository provided by the DevOps team into the proper location on the storage server at the Stratos Data Center.

## Task Details
- **Source Repository:** `/opt/official.git`
- **Target Directory:** `/usr/src/kodekloudrepos`
- **Method:** Cloned using Git without any changes to maintain integrity

## Key Commands
```bash
sudo git clone /opt/official.git /usr/src/kodekloudrepos
