# GIT INTRODUCTION

<img src="https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png" alt="git logo" width=200>

## What is GIT?

Distributed version control system. 

Best for personal daily workflow and sharing of code within a team.

### Where do you get it?

- You can download **GIT for Windows** from [https://git-scm.com/](https://git-scm.com/)
- The software can be installed by IT Department if you don't have administrative rights to your computer or Virtual Machine.

### Software that can access and update GIT repositories without a local version of GIT installed

- SQL Developer.
- VisualStudio IDE.
- Spyder IDE.

## Git Concepts

**Staging** - The process of identifying files that should be tracked by git. Multiple files can be staged in preparation for a single commit or 'published change' in the repository.

**Committing** - The process of publishing a set of changes in the repository. Only staged files are committed. Use `git status` to see if there are unstaged changes in the repository.

**Local and remote repositories** - git is a distributed version control system. All code is stored in every repository in the network. Changes in code can be managed locally through staging and committing changes, and the state of the repository changed to any commit point using `git checkout {commit}`. Changes can also be shared to the remote repository using the `git push/pull` commands.

**Pushing** - The process of pushing committed changes in a local repository to a remote repository like GitHub or Azure DevOps Repositories.

**Pulling** - The process of pulling committed changes in a remote repository like GitHub or Azure DevOps Repositories to a local repository.

**Cloning** - The process of duplicating a remote repository usually in GitHub or Azure DevOps Repositories to a local directory. Cloning also sets the remote repository to the cloned repository.

**Branching** - The process of creating a namespace or named sandbox where changes can be made that remain distinct and separate from the main or master code.

**Merging** - The process of merging committed changes in a branch with the main or master code.

## Help

If you install **Git for Windows** you can type `git --help` in the **Git Bash Terminal** (available when you right click a folder or the Start Menu)

Resources can be found on the **GIT for Windows** website [https://git-scm.com/](https://git-scm.com/)

## eBooks and Cheatsheets

- <a href="https://git-scm.com/docs">Git Reference Manual</a>
- <a href="https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf">GitHub-Git Cheat Sheet</a>
- <a href="https://git-scm.com/book/en/v2">Pro Git eBook</a>
- <a href="https://git-scm.com/videos">Git Learning Videos</a>
- <a href="https://docs.microsoft.com/en-us/azure/devops/project/wiki/markdown-guidance?view=azure-devops">Markdown rendered in VSTS</a>

## More tutorials

- [Basic Use](basic_use\GIT_Basic_Cheatsheet.md)

## Licenses

Software developed under this project is being released under a [GNU General Public License, version 3 (GPL-3.0)][2] license.

Supportive documentation is released under a [Creative Commons Attribution 4.0 International (CC-BY)][3] license.


