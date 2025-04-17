## Task: Push Sample index.html to Remote Repository

The objective of this task was to:

- Copy the sample `index.html` from the jump host (`/tmp/index.html`) to the storage server inside the cloned repository at `/usr/src/kodekloudrepos/apps`.
- Add and commit the file using Git.
- Push the changes to the remote repository on the `master` branch.

### Commands Used:

```bash
# On the jump host
cd /tmp
python3 -m http.server 80

# On the storage server
cd /usr/src/kodekloudrepos/
wget http://example.com/tmp/index.html          # change "example.com" 
git add apps/index.html
git commit -m "Add sample index.html to apps directory"
git push origin master
