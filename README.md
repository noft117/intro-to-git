- git add - will take the file from the working directory to the staging area-
- git status - will show if we have anything that needs to be commited.
- git commit -m "message here" - will commit the snapshot. "Present tense - verb indicate what you are doing".
- git log - will show you the history of your snap shots
- git add *.html (or different file type doesnt have to be .html) - Adds all file types to the staging area.
- git add . - will add all the files to the staging area.
- git add -A - add all files and folders from the directory you are in even hidden files. this is a good command for adding everything
- in your project at one time
- git reset HEAD <file> will remove a file.
- mv <file u want to change> <new file name> - can rename from console

# Working Directory
- Area where all of our files and directories and changes are living all the time

# Staging Area
- git status will show if we have anything that needs to be commited.

# Git Repository
- Where all our snapshots are stored.

# Git Branches
- Listing all branches
- git branch
 
- Adding a branches
- git checkout -b <branch_name>

- Changing branches
- git checkout <branch_name>
 
- Merging a branch
- git merge <branch_name> 
- remember to checkout into master branch then merge it into the master branch.

- Removing a branch
- git branch -d <branch_name>

Branch representation:
         /-----0---0----0
        /          / <-merge or fast foward
0------0----0----0----0

0 = commits,
/ = new branch