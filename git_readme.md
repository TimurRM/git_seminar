# Using branches in control versions

* To rename branch run **git branch -m <name>**
* To create new branch run **git branch <branch_name>**
* To merge branches run **git merge <branch_name>**
//First you need to checkout to the "main" branch, than use this command with the upcoming changes branch name//
* To delet barnch run **git branch -d <branch_name>**

# Homework (create 4 branch and merge with some conflict)

1. To rename commit text run git commit --amend -m "New text"
2.  To briefly display the log run **git log --oneline**
3. To see all branchs log run **git log --all**
4. To create new branch with switching at it run **git checkout -b <branch_name>**
5. To see the latest commit on each branch run **git branch -v**
6. To rename the banch run **git branch --move <previous_name> <new_branch_name>**
7. To send <_new_branch_name_> to the remote repository run **git push --set-upstream origin <new_branch_name>**
8. To delete previous branch in the remote repository name run **git push origin --delete <previous_name>**
9. To abort the merge process and try to reconstruct the pre-merge state after the merge has resulted in conflicts run **git merge --abort**
10. To run after the merge has resulted in conflicts run **git merge --continue**
10. git merge --continue") can only be run after the merge has resulted in conflicts.