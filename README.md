## -- ## GIT COMMAND
-- ## CHECK VERSION
git --version

-- ## ADD CONFIG DETAILS
git config --global user.name "Your_Username"
git config --global user.email "Your_Email_id"

-- ## SHOW CONFIG DETAILS
git config --global user.name
git config --global user.email

-- ## EDIT CONFIG DETAILS  
git config --global --edit

-- ## CREATE NEW REPOSTORY
git init

-- ## CHECK STATUS
git status

-- ## ADD CHANGES FILE 
git add . OR git add -A
git add routes/web.php

-- ## COMMIT  
git commit -m "COMMIT MESSAGE"

---------------------
-- ## ADD CHANGES WITH COMMIT FILE 
git add .; git commit -m "COMMIT MESSAGE"
---------------------

-- ## PUSH
git push origin branch_name

-- ## FORCE PUSH
git push -f origin branch_name

-- ## LIST OF COMMIT 
git log

-- ## LIST OF BRANCH 
git branch

-- ## CREATE NEW BRANCH 
git branch branch_name

-- ## SWITCH BRANCH 
git checkout branch_name

-- ## CREATE NEW BRANCH WITH SWITCH BRANCH 
git checkout -b branch_name

-- ## MERGE BRANCH 
git merge master

-- ## CREATE FILE gitignore
touch .gitignore

-- ## RESTORE FILE
git restore file_name

-- ## WHEN EVER YOU WANT TO BACK COMMIT CHANGES
git stash
git stash pop
git stash clear

-- ## RESET COMMIT
git reset COMMIT_ID

-- ## RESET HARD
git reset --hard branch_name

-- ## RESET HEAD
git reset --soft HEAD~1

-- ## REBASE --> Lot's commit store with single command
git rebase -i COMMIT_ID

pick --> means takeing this commit 
squash --> use commit, but meld into the previous commit
reword --> use commit, but edit the commit message


## -- ## COMMON LINUX COMMAND
-- ## CREATE NEW DIRECTORY
mkdir
-- ## LIST WITH FILE AND DIRECTORY
ls
-- ## LIST WITH HIDDEN FILE AND DIRECTORY
ls -a 