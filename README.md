### GIT Install


### GIT Basics
**ACTIVATE** GIT for project (Needs to be in **correct folder!!**)
```
git init
```
Check if something **CHANGED**
```
git status
```
If you made a change in file and you want a **new version in project mark/ADD**
```
git add index.html
```
**CONFIRM** the change **(always add the comment!!!)**
```
git commit -m "added index.html"
```
Check the **HISTORY** of the project (q-key quit the log file)
```
git log
```
### GIT Basics more 
Mark **ALL** files in a folder (no deleted files)
```
git add .
```
If you want **CANCEL** marked/added files
```
git restore --staged .
```
Commit **ALL CHANGES** (not new) files  
Adding comment
```
git commit -a
git commit -am "Add a comment here"
```
Check the **HISTORY/LOG** in oneline
```
git log --graph --decorate --abbrev-commit --all --pretty=oneline
```
**REVERT** *index.html* to old version from git
```
git checkout -- index.html
```

### GITHUB Basics
**CREATE** repository on GITHUB  **(SSH key is necessary to create)**

Clone project into folder **(if the repo is new)**
```
git remote add origin git@github.com:Blackchickenn/101_Git_GitHub_Cheatsheet.git  
git branch -M main  
git push -u origin main
```
Clone project into folder **(if the repo is already created)**  
SSH  
HTTPS
```
git clone git@github.com:Blackchickenn/101_Git_GitHub_Cheatsheet.git  
or  
git clone https://github.com/Blackchickenn/101_Git_GitHub_Cheatsheet.git
```
**PUSH** changes from local to GitHub (Login name and password)
```
git push origin main
```
**PULL** changes from GitHub to local (Login name and password)
```
git pull origin main
```
**CHECK** if there are some **CHANGES** on GitHub
```
git remote update
git status
```
Check **who** and **what** kind of changes were made
```
git whatchanged origin/master -n 1
```

### GIT Branch
Check **BRANCH/ES** in project
```
git branch
```
**CREATE** new *login* branch
```
git branch login
```
**ENABLE/SWITCH** to *login* branch
```
git checkout login
```
**MERGE** *login* into main branch
```
git checkout main  
git merge login
```
### CHEAT SHEETS
- https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf  
- https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet 