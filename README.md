# GitHub Basic Commands
pwd  : present wroking directory

cd : change directory

stagging area : staging area contains files which we dont want to commit in next commit

git status

git init

git add --a  //all chnages at stage

git commit -m "message"

git log  // to check details of committing

// make changes in files and run 
git status

// modified files wil be viewed.
git add fileName want to commit

rm -rf .git   // to remove git from folder

touch error.log   //creates  error.log file

touch .gitignore   //creates .gitignore file
 // to ingonore .log file just add *.log in .gitigonore file

git diff   // to compare files of staging and modified

git diff --staged 


git mv oldName newName  // to rename file in git

git rm --cached fileName  //remove file from tracking

git log -p  compete changing  log

git log --stat

git log --pretty=oneline,short
git log --since=2.days  // previous two days work check

git log --since =2.weeks
