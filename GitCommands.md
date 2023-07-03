# Git Commands
#### Belows commands  & instrcutions are used to Commit, Push, Pull etc in Git.

(Open Project folder -> right click -> Git Bash Here or navigate to Project directory i.e cd )

###### Configuring Git
- git config --global user.name "My Name"
- git config --global user.email "myEmail@example.com"

###### Creating a new Repository
- git init

###### Checking the status
- git status

###### Staging
- git add
- git add hello.txt
- git add .  (add everything)

###### Commiting
- git commit -m "some commit message"

###### Connecting to a remote repository & Push the code to Remote
- git remote add origin https://github.com/ganesh-bhosale/GitDemo.git
- git push -u origin main

###### Add file and Push
- git add .
- git commit -m “some comment”
- git remote add origin https://github.com/ganesh-bhosale/GitDemo.git
- git push -u origin main

###### Cloning as Repository
- git clone https://github.com/ganesh-bhosale/GitDemo.git

###### Getting changes from a Remote Repo to Local
- git pull origin main
