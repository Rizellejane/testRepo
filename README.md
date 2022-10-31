Basic Git commands 

git clone  repository_name : get/create clone of project from the repository

git commit -m : create ( commit message ) discription of change
  
git push : push the changes to repo
git branch branchname :create new branch from master branch opr any base branch
git branch -m : rename ang branch
git checkout -b : create new branch checkout named branch
git checkout: checkout to new branch

git add 
 - . :means all changes from the root directoy
 - filename = specific changes only
 ex. git add filename_1 filename_2

git reset HEAD
 - 1 current Head or commit ID
 ex. git reset HEAD~1 

git log : check all commit id or log history

git status : check changes in the file

git config -l : check current git configuration
git config --global user.name 'rizelle jane' : set username
git config --global user.email 'viscaynorizellejane@gmail.com' : set email

git remote set-url origin https://github.com/Rizellejane/testRepo.git/: set new origin url