# Working Directory
- Area where all of our files and directoires and changes are living all the time

# Staging Area
- Files and directories that we explicitly add to the staging area

# Git Repository
- Where all our snapshots are stored

# Important commands
- git init
- git status
- git add
- git commit -m "Message Here"
- git log
- Q to exit git log

# Adding multiple files of a certain type
- git add *.html (uses wildcard to match all file types)

# Adding all files in directory including hidden files
- git add -A

# Remove a file off the staging area
- git reset HEAD <file>

# ignore files
- .gitignore file in directory
- Any file names in this file will not be tracked

# Git branches
- Listing all branches
    git branch
- Adding a branch
    git checkout -b <branch_name>
- Changing branch
    git checkout <branch_name>
- Merging a branch
    git mergre <branch_name>
- Removing a branch
    git branch -d <branch_name>

# Connecting to github
- add C9 ssh key to your github account
- create a new repository
- git remote add origin <url> (add remote)
- git remote -v (check version)
- git push -u origin master (pushes the local repository to github repository)

# Test
- asdasdasdsadsadasd
- git push - u origin master (need to do this everytime to have changes reflect on github)