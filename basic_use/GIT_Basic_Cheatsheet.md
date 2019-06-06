# GIT BASIC COMMANDS

<img src="https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png" alt="git logo" width=200>

### Initialize GIT repository

- `git init`
- .gitignore

### Cloning Repository

git clone {remote repository on GitHub, GitLab or VSTS}

### Identify yourself as the main user

`git config --global user.name "Your Name"`

`git config --global user.email "Your Email"`

### Local Repository Management

`git status`

`git add filename`

`git add *`

`git commit -m "Initial commit"`

`git commit -a -m "Initial commit"`

### Adding to or developing code

`git branch new_branch`

`git checkout new_branch`

`git checkout master`

`git merge new_branch`

`git branch -d new_branch`

### Remote Repository Management

Daily PUSH and PULL

Not everyone has rights to create a repository on VSTS so option is to clone a remote repository

`git push`
