# GitHub Foundations 

## Git Hidden Folder
There is a hidden folder called '.git' which tells you that our project is a git repo.

If we want to create a git repo in a new project we'd create the folder and initialize that repo using 'git init'

```sh
mkdir /workspaces/tmp/new-project
cd /workspaces/tmp/new-project
git init
touch README.md
code README.md
git status
git add Readme.md
# makes changes to README.md 
git commit -m "add README file"
'''

## Cloning
-We can clone three ways:  HTTPS, SSH, and CLI
-Since we are using GitHub Codespaces we'll create a temporary directory in our workspace
```sh 
mkdir /workspace/tmp
cd /workspace/tmp
```

### HTTPS
```sh
git clone https://github.com/MrChiff/Github-Examples.git
cd Github-Examples
```

## Commits

## Branches

## Remotes

## Stashing

## Merging

## Reset

Reset (git reset) allows you to move Staged changes to be unstaged.
This is useful to revert all files not to be committed.
```
git add .
git reset
```

> git reset will revert a git add .