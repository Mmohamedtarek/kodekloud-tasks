# Git Bare Repository Setup on Remote Server

## Description
This task was part of a hands-on lab on KodeKloud simulating a real-world DevOps scenario.

## Tasks Performed
- Connected to a remote storage server via SSH
- Installed Git on the server
- Created a **bare Git repository** to act as a central remote repository
- Verified network connectivity and server setup using basic Linux commands

## Key Commands Used
```bash
ssh user@storage-server
sudo apt install git
git init --bare /opt/git/myproject.git

