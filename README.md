# prac
my first practice with github repo

install: git-scm , 
open: git bash, 
check: git --version, 
for list items: ls, 
create new file in local repo : touch file-name, 

STEP 1 (cofigure your credentials in local machine for the first time )
git config --global user.name "user name" 
to check username : git config user.name 

STEP 2 (cofigure your credentials in local machine for the first time )
git config --global user.email "emailaddress@gmail.com" 
to check user email : git config user.email 

STEP 3 (Initialize the folder of the project i.e it creates ".git" hidden folder)
git init 

STEP 4 (to add or add all files and folders i.e getting the files ready)
git add file-name or git add . 

STEP 5 (set origin to remote repository)
git remote add origin http-link-address-from-git-repository 

STEP 6 ( commit message if something opens then :wq)
git commit -m "message-here"

STEP 7 ( push local repo as master branch, -u for update)
git push -u origin master
