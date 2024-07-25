#Git branch

git branch <branchname> to create new branch
git checkout <branchname> to swith to desired branch
git checkout -b <branchname> create branch and switch to it

git diff <branchname1> <branchname2> to see differences between 2 branches
git diff <commit-hash> <branchname> since branchname is actually 
a commit pointer 

to merge branches you need:
1. Switch to master branch (or branch which you want to apply your changes)
2. use git merge <branhcname> to merge master (CURRENT SELECTED BRANCH) branch with <branchname>.
Changes in <branchname> will apply to master (CURRENT SELECTED BRANCH) or there will be merge conflict.
Figure out how to fix it urself
