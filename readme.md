# Git

## Git Topics
1. Working Directory - Area where all of our files and directories are living all the time
2. Storing Area - Files and directories that we explicitly add to the storing area
3. Git Repository - Where all our snapshots are stored

## Git Basics
* git init
* git status
* ls -a - shows files & directories including hidden
* git add <file>
* git add . - add all files & folders
* git add -A - adds all files & folders
* git add *.js - add multiple files of a certain type
* git reset <file> - undo a git add file befor commit
* git commit -m "message"
* .gitignore - ignore files & folders

## Git Checkout
* git log - shows git history
* git checkout commit-id - changes to that commit
* git revert --no-commit 0766c053..HEAD

## Git Branches
```
        Feature or New Branch
       /----0----0--0--0
      /                 \ merge
0----0----0----0---------0   
master branch
```
* git branch - listing all branches
* git checkout -b branch_name - adding a branch
* git checkout branch_name - changing branches
* git merge branch_name
* git branch -d branch_name - remove a branch

## Cloning and Github Intro
* What is Github?
* clone github_url - Cloning an existing repo

## Pushing to Github
* Creating a repo on github
* Using ssh key, e.g. c9: git remote add origin git@github.com:foyezar/repo_name.git - Adding a remote connection
* Using laptop or destop: git remote add githubRepo https://github.com/foyezar/repo_name.git - Adding a remote connection
* git remote -v - check remote connection
* git push -u origin master - Pushing to github
