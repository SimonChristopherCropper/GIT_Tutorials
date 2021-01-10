# GIT BASIC COMMANDS

<img src="https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png" alt="git logo" width=200>

## Initialize GIT repository

`git init` - the command to create a git repository. This is one method of creating a respoitory. The other is to clone a remote repository.

`.gitignore` - A text file listing the files or directories that are ignored by git. This is good mechanism to exclude data types or programming language artifacts being synced with remote servers.

## Cloning Repository

`git clone {remote repository}` - creates a clone of the remote repository in the current directory and sets the URL as the remote repo updates are sent if you push your changes. An alternative way of creating a repository is to initialize a repository.

## Identify yourself as the main user

`git config --global user.name "Your Name"` - identifies the author of any changes in the local repository.

`git config --global user.email "Your Email"` - identifies the contact email of any changes in the local repository.

## Local Repository Management

`git status` - the output from this command tells you where you are up to in your workflow and suggests the next step in the process.

`git add {filename}` - adds a file to the repository index. This essentially tells git to track a file. This is referred to as staging a file.  Multiple files can be staged to committed as a group of changes.

`git add *` - adds all changed files to the repository index.

`git commit -m "Initial commit"` - commits all the changes in the staged/watched files to the repository and takes the changes with the message in the inverted commas. Each commit has a unique code that allows the user to return to this place anytime in the future regardless of how many changes have occurred after the commit is done. If you omit the `-m ""` the default editor is invoked asking you why you made the changes. 

`git commit -a -m "Initial commit"` - this is a hybrid shortcut. This command adds all the changes in the watched files and commits them.

## Adding to or developing code

`git branch new_branch` - creates a branch. A branch is like your own personal sandbox where ideas can be trialled or developed. 

`git checkout new_branch` - changes the repository environment to the branch's state. All commits from this point on will be attributed to the 'current/open' branch.

`git checkout master` - returns the repository environment to the state before the current branch was created.

`git merge new_branch` - merges the committed changes in a branch to the current branch (usually master).

`git branch -d new_branch` - deleted branch.

## Sharing changes with remote repository

`git push` - pushes committed changes to the remote repository originally cloned when you created the git repository.

## Look at who has done what recently

`git log --pretty=format:"%ad - %an -- %h : %s"` - Prints the commit log to screen in readable format

## Licenses

Software developed under this project is being released under a [GNU General Public License, version 3 (GPL-3.0)][2] license.

Supportive documentation is released under a [Creative Commons Attribution 4.0 International (CC-BY)][3] license.


## Licenses

Software developed under this project is being released under a [GNU General Public License, version 3 (GPL-3.0)][1] license.

Supportive documentation is released under a [Creative Commons Attribution 4.0 International (CC-BY)][2] license.


[1]: https://opensource.org/licenses/GPL-3.0
[2]: https://creativecommons.org/licenses/by/4.0/legalcode


