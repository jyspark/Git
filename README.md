# Git

Initialize the local directory as a Git repository.
  $git init
Add the files
  $git add file_name    #or git add . 
#Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'

Commit files
  $git commit
#Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.  

Connect github
  $git remote add origin repositURL
  $git remote -v      #verifies the new remote URL

Push the changes
  $git push origin master

or do $git pull --rebase origin master then push
