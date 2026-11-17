# git commands

```text
git mkdir - for new folder
cd - change directory
touch - for new file inside the folder
open . - to see the current folder
git status - to check which file have been modified
ls - to check what are the files inside the folder
git add --all *or* git -A - to move all the files at once
git reset - to reset all files as same as before
git add . - stages the changes within the current directory you’re in
git add * - only stages new or modifed files for eg: if i directly deleted and added any of the file from the folder and check git status it shows the file is untarcked so if we use this cmd
git add <*file name*>.txt - to add indiviual file 
git commit -m “ “ - to commit the changes what we had done
git reset ~HEAD - brings everything back to working directory even after commit changes
git rm <*file name*>.txt - if we want to delete a file and stage it directly
git reset --hard - to bring back all the deleted files to its folder
git rm -f <*file name*>.txt - to forcefully or completely delete the modifed file
git rm --cached <*file name*>.txt - this only unstage the file but wont delete form the main folder
git rm -r <*folder name*> - deletes everything like folder and its files
git log - instantly to see the full commit history
git log --oneline - to see the short summary of commits
git branch - this cmd shows all the branches
git branch <*branch name*> - to create a new branch
git checkout <*branch name*> - to switch to another branch
git merge <*branch name*> -m “ “ - to merge the branches
git diff <*commit id 1 and commit id 2*> - exact changes made b\t this 2 commits
git push origin main - to eveything changes from local machine to git hub
git fetch - to bring the latest changes from the remote 
git pull - which acts as  both fetch and merge of the changes in local files
git restore <*file name*> - restores the file that we dont want the new changes done by us makes the file as before
git restore <*directory name*> - to restore entire file of that directory as before
git restore . - this restore every file to last commited state
git restore --stagged <*file name*> - bring the file to unstaged state
git restore --staged . - bring all the files to unstaged state 
git stash - temporarily set aside your unfinished work, switch to another branch to so something
git stash pop - to bring back all the stash changes to working directory and removes from the stash list 
git stash list - to check list of all the saved stashes
git stash apply -  to bring back all the stash changes to working directory but wont remove from the stash list and keep it for the feature use
git rebase <*branch name*> - to bring the new updated to another branch without anychanges
```