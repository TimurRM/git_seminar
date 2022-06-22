# Using branches in control versions.
* To rename branch run **git branch -m <name>**
* To create new branch run **git branch <branch_name>**
* To merge branches run **git merge <branch_name>**
//First you need to checkout to the "main" branch, than use this command with the upcoming changes branch name//
* To delet barnch run **git branch -d <branch_name>**

# Homework

* To rename commit text run **git commit --amend -m "New text"**
* To briefly display the log run **git log --oneline**
* To see all branchs log run **git log --all**
* To create new branch with swiching at it run **git checkout -b <branch_name>**
* To see the latest commit on each branch run **git branch -v**
* To rename the banch run **git branch --move <previous_name> <new_branch_name>**
* To send new branch name to the remote repository run **git push --set-upstream origin corrected-branch-name**