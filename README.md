# GIT_notes
## Check installation ##
``` git --version ```
## Set username ##
```  git config --global user.name "name"  ```
## Set email ##
``` git config --global user.email "email" ```
## Check if email is set or not ##
``` git config --global user.email  ```
## Check if username is set or not ##
```  git config --global user.name  ```
## Change userame and email from file by editing config file ##
``` git config --global --edit ```
## Initialize git repo (execute in repo folder) ##
``` git init ```
## Display status history of changes in repo (displays branch, commits, tracked and untracked files)(also tells files that are modified)##
``` git status ```
## Add file to track (add file in staging area) ##
``` git add file_name ```
## Add all files in folder to track (add all files in staging area) ##
``` git add . ```
## Staging area ##
If file is added with ```git add``` command then it is staged and will be commited in next commit.
## Commit (commit message is some sort of identification for story being developed or what changed carried out) ##
``` git commit -m "commit_message" ```
## Get details of all commits ##
``` git log ```
## After every commit, file that was commited earlier needs to be added again to staging for commiting in next commit ##
## Before every commite, we need to add and stage all files whose changes are to be commited in main branch ##
## Hash code ##
In Git, a hash code (or more commonly known as a commit hash or commit ID) is a unique identifier assigned to each commit in the repository. The hash code is a cryptographic hash function, specifically a SHA-1 hash, generated based on the contents of the commit and its metadata.
## Go to earlier commits (all existing changes which are not commited will be lost) ##
``` git checkout hashcode```
## Get the latest repo from server OR Switch to master branch ##
``` git checkout master ```
The command git checkout master is used in Git to switch to the "master" branch. The "master" branch is a default branch created by Git when you initialize a repository, and it's commonly used as the primary development branch or the main branch of a project.
## Branch ##
There exist one main branch for each project. For development, different branches are made and finally merged into main branch called as master.
## Make branch ##
``` git branch branch_name ```
## List the branches ##
``` git branch ```
## Activate some branch ##
``` git checkout branch_name ```
## Dev branch is made from master branch for development purpose and all individual stories are developed within individual branch of dev branch having same number or ID as that of story number or ID. Once all development is over, all individual story branches are merged with dev. Then dev branch is checked. If all is found to be ok then it is merged with master branch.
## Make new branch and checkout  ##
``` git checkout -b branch_name ```
## Merge branches (to be executed with checking out the branch to which the other branch is to be merged) ##
``` git merge branch_name ```
## File never to be tracked ##
Make a file with name ``` .gitignore ```
Add all files and folder names in this file which are to be ignored
## Get reference to local repo in github ##
``` git remote -v ```
## Get details of local repo reference to github repo ##
``` git remote -v ```
## Relate local repo to github repo ##
``` git remote add origin <url> ```
## Push commits to github ##
``` git push -u origin master ```
## Push other branches to github ##
Checkout other branch to be pushed to github, then ``` git push -u origin other_branch_name ```
## ##





