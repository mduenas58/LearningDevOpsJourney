How to rename a branch on GitHub

If you have a local clone, you can update it by running the following commands after renaming the branch on GitHub:

1- git branch -m main master (main was the old branch name and been changed to master)
2- git fetch origin
3- git branch -u origin/master master
4- git remote set-head origin -a
