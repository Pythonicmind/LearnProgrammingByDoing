# Basic of Git installation and working

# Installation
 1) Go to https://git-scm.com/
 2) Go to download and download the appropriate installer for Windows or Mac or Linux.
 3) During Installation -> Select "Use Git from Git Bash only" for initial purpose and for line ending choose         "Checkout windows-style, commit Unix-style line endings"

 # Use Local repository

 1) Open Git Bash
 2) Run "git init" to initialize the git repository at the project location and you will see a hidden ".git" will create
 3) Create a text file "readme.txt" in the location.
 4) *git add readme.txt* -> This command will add the text file to git repository  
 5) *git status* ->status of readme file
 6) Now we are "staging state". So new changes will need add again.  
 7) VM text editor will come insert mode after pressing "I" then type  "initial Commit" then press "Esc" and ":wq"
 8) If you don't have VM editor then use command "git commit -m change3"
 9) git log -> will give you commit history

# Multiple Branching
 1) git branch newBranch -> Will create a new Branch
 2) git Checkout newBranch -> Will move to new Branch
 3) git Checkout master -> back to master Branch
 4) git status -> On which branch you are working
 5) git merge newBranch-> it will merge the branch to master

 # During Merge Conflict
 1) Can see the merge Conflict in the readme file
 2) Remove the merge Conflict in readme file
 3) git commit -a -m 'merge from master'
 4) git status

 # Re-basing in the git-> Always rebase(update from master for latest check in)

# git stash-> To clean the directory
 In situation where you have un-commited changes on your branch and you have to work on master Branch for some fix then un-commited changes will create the issue. So we will use "git stash" command to make it staging and can commit any time.
