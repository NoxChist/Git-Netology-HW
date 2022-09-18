# Git commands note
### Create ssh

ssh-keygen
cat ~/.ssh/id_rsa.pub

### Git global config

- git config --global user.name ""
- git config --global user.email ""
- git help -g (or command)
- git config --global --list

### Work with repository

- git init
- git status
- git add -A
- git commit -m ""
- git commit --amend -m "" 
- git log --oneline
- git checkout hash (git checkout -)

#### Remote commands

- git remote -v
- git remote add origin ssh-link 
- git remote remove origin 

#### Branch. 

git branch 
git log имя-ветки --graph --oneline
git merge (branch name)