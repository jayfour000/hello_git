# hello_git
Sample code for Hello Git presentation

### Your first Git
```
// Make a directory to put project code in
mkdir ~/work

// Change directory to the folder you just made
cd ~/work

// Make a directory for this project
mkdir hello_git

// Change directory to the folder you just made
cd hello git

// Clone (download) the Git repository to your local machine
// Option 1 - With HTTPS
git clone https://github.com/jayfour000/hello_git.git

// Option 2 - With SSH
git clone git@github.com:jayfour000/hello_git.git

// Check out the `develop` branch
git checkout develop

// Make sure you are synced with origin
git fetch

// (optional) pull down any new changes
git pull

// Make a new feature branch
git branch feature/add-feedback-form

// Check out the new branch you just made
git checkout feature/add-feedback-form

// Make some code changes and see the status of what you changed
git status

// Add the changes
git add .

// Create a new commit that includes the changes
git commit -m"Chagned the feedback form"

// Push (upload) the changes to origin
git push







```
