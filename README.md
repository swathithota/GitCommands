# GitCommands
# GitCommands

 1. Git resolve conflict
 
  git checkout develop
  
  git pull develop
  
  git checkout <your branch name>
  
  git rebase develop
  
  //git add .
  -- after these commands you will see all conflicts you need to see what you want to keep in develop based, 
  after that 
  
  git rebase --continue
  
  git push -f
  
  2.CHERRY PICK
  Go to your repo(master branch)
  
  Copy git commit id for develop not your branch
  
  git  cherry-pic <commit_id>
  
  //it will show all files with that commit id will be  added to your new repo
  
  Git push-f
