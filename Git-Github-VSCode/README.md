What: Get familiar with Git, Github, and VSCode
Why: to be efficency in coding
How: Using online materials to learn and practice
Source: https://www.youtube.com/watch?v=DVRQoVRzMIY&ab_channel=TechWithTim

What is Git / Github?
-Git: a version control system, running on local machine. 
-Github: GUI hosted git
Track all the changes. 
Historical backup all the "snapshots". 
Team based development. 
Flexible - Can work localy/remotely
CLI vs web
Trunk-based development: can create branches, which each can work independently and merge after finished/tested

-Repository /Local repository/ Remote repository
Place to store the codes and changes of them.

-Clone vs Pull
git clone: create a copy of an existing repository
git pull: update the local copy with the new commits from the remote repository.
-Commit
-Push
-Master / branch
-Merge / conflict
-Pull request(PR): Changes that need to approved and merge to the branch/master
-Initalize a git repository: -> can use git command after, everything in this repository is tracked by git
git init

-Add a file : not yet commit, just add the changes to the staging area.
git add [name] : add a file to staging area
git add . : add all files 

-Check status
git status

-Commit
git commit -m "describe"

-Create a new branch:
git checkout -b new : switch to a new branch "new"

-Change back to the master branch:
git checkout master

-Merge to a branch:
git merge master/[branchname]

-Add a remote repository
git remote add origin/[name] [link]

-Push changes to remote repository
git push -u origin/[repositoryname]/[destination] master/[branchname]/[location]
-u: save the setting of this command, next time we only need to use: git push

-Pull changes from github
git pull origin/[remoterepositoryname] master/[nameofthebranch]

-set up global name, that recognize in github
git config --global user.name "Nate"
git config --global user.email "[email]"
cc