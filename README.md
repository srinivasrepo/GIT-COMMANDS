# prac

/////////////
GIT COMMANDS
////////////
install: git-scm , 
open: git bash, 
git --version : check , 
ls : for list items , 
touch file-name :create new file in local repo , 
git log : to show git all commit names with time and date or log data ,
git add file-name or git add . : (to add file or add all) , 
git rm file-name or git rm . : (to remove file or all) ,
git push : (to push your latest changes from local repo to remote repo) ,
git pull : (to pull or get latest changes from remote repo to local repo) ,
git branch : (to list all your branches),
git checkout branch-name : (to create and switch to branch by a single command i.e work tree) , 
git checkout master : (to get back to master branch ),
git stash : (save changes that you dont want to commit immediately), 
git merge branch-name : (to merge branch with master),
git reset or git reset --hard first-five-letters-of-commit-id: (to reset back to before the commit permanently i.e alter existing                                                                      history),
git revert : ( creates the new commit that undoes the previous commit  i.e adds new history, it doesn't modify existing history)
git remote : (to check what remote source you have),
git status : ( to show what files have changed in local repository while comparing it to the remote repository )
git diff : ( to show the changed files changed text i.e (git status files) the changed files changed text in green color while comporing            to past text in red color )






/////////////////////////////////////////////
STEPS TO ADD LOCAL REPO TO GITHUB REMOTE REPO
////////////////////////////////////////////
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




//////////////////////////////////////////////////////
STEPS TO CLONE REMOTE GITHUB REPO INTO OUR LOCAL REPO
/////////////////////////////////////////////////////
STEP 1 (only one single step)
git clone git-hub-https-address




//////////////////////////////////////////////////////////
STEPS TO UPDATE GITHUB REMOTE REPO FROM CHANGED LOCAL REPO
/////////////////////////////////////////////////////////
STEP 1 ( check which files changed ,here we can also monitor staged files i.e added for update in git add <file name with path>)
git status

SPEP 2 ( check what is the difference between recent text or content of recent file and previous file)
git diff

STEP 3 ( add each file to getting ready for commit i.e to stag the not-stagged , synrtax : git add <each file name with path> , likewise          add all)
git add file-name-with-path
  
STEP 4 ( commit with -m message)  
git commit -m "message-here"

STEP 5 ( check the remote url)
git remote -v

STEP 6 ( now push stagged files)
git push -u origin master


//////////////////////////////////////////////////////////
STEPS TO UPDATE LOCAL REPO FROM CHANGED GITHUB REMOTE REPO
/////////////////////////////////////////////////////////
git pull

























































