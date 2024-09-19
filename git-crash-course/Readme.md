## GitHub hidden repo 

There is a hidden folder called `.git` which tells you that are repo git folder.

If you want to new project and initalize 

```md
mkdir /workspaces/tmp/new-project/
cd /workspaces/tmp/new-project/ 
git init
touch Readme.md 
code Readme.md
git status
git add . 
git commit -a -m "add the readme.md"
```

## Cloning 

we can be clone 3 ways: HTTPS, SSH, GitHub CLI 

```sh
mkdir /workspaces/tmp/ 
cd /workspaces/tmp
```

### HTTPS
```sh
git clone https://github.com/ThanHtutPC/learning-git-foundations.git
cd learning-git-foundations
```
## commit
when you commit code we can write git commit which will open up the commit message and log will deploy with log_id.

```sh
git add.
git commit -a -m "update the code"
```

## branches

## merging 

## staging 

## repository

## codespaces

## reset

stage change to unstage file and all file will appear to untrack stage.
This is useful when you want to revert to all file not to be commited. 

```md
git add . 
git reset

```