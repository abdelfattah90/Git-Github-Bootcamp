## The most git commands used

#

Initialization git in working directory

```
git init
```

Clone repository to working directory

```
git clone repo_url
```

Show files status

```
git status
```

#

Add all files

```
git add .
```

Add a file to staging area

```
git add filename.js
```

#

Descried what you do after that The files will be moved from staging area to local repo

```
git commit -m "init file"
```

git list of commits

```
git log
```

#

Undo add a file to staging area

```
git reset head filename.js
```

git revert last commit

```
git reset --soft HEAD~1
```

#

Add files to repo

```
git remote add origin url_repo
```

Show remotes

```
git remote -v
```

#

Pulling all file or a new files from repository to working directory

```
git pull origin
```

#

push origin master

```
git push remote_name branch_name
```

```
git push -u origin master
```
-u = pull and push files to repo


#

create a new branch

```
git checkout -b branchName
```

push a new branch

```
git push origin branchName
```

Show branchs on local repo

```
git branch
```

Delete branch from repo

```
git push origin --delete branchName
```

#

Show all configurations commands

```
git config -l --show-origin
```

Show email

```
git config --global user.email
```

Remove email account from the device

```
git config --global --unset user.email
```

confirm email

```
git config --global user.email "email@gmail.com"
```

#

#

<img align="center" src="https://raw.githubusercontent.com/abdelfattah90/The-Most-Git-Commands-Used/main/git.png" alt="git" />
