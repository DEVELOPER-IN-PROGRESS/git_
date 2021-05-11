# __git__
A Collection of git commands that i use most of the time


git init  >>  Initializes a project directory into a git directory 

git add <filename> 

git add  .            bundles the collection of files on which changes are made

git commit -m "<meaningful commit message>"   describe the change(s)  you have made in your project at the time of that commit
  
git log --oneline                             A log file of all the commits made

git remote add origin <remote repo link>      adds your github/target repository link to a variable called origin so that variable can be used instead of URL 

git push origin <branch name>                 Pushes all the commits made into remote repository 
  
git pull origin main                          Pulls in all changes from a remote repository . This is usually done when changes are made in remote repository 
                                              while working on local repository to avoid merge conflicts 
                                             
git stash                                     bundles all modified changes .This  is usually done when we dont want to commit , but want to pull in latest changes

git shash pop                                 All stashed changes are popped back into local workflow .MAinly Done after pulling changes from remote repository
  
git branch   <branch name>                    Creates a new branch in the workflow  other than main/master branch 
  
git checkout <branch name>   ::               Switches from working branch to target branch 

git merge <branch name>      ::               Merges  target branch to current working branch 

git branch -d <branch name>                   Deletes the target branch .Usually done after the required features or testing are done
  



