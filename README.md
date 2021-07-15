## Git Cheat Sheet

Brief reference of various git commands. Also practice with git branching

-   `git init` - Initialize a local git repo in working directory
-   `git status` - show state of the local repo
-   `git log` - list commit history
-   `git log --oneline` - Compact commit history
-   `git config -l` - show your git configuration settings
-   `git commit -m "msg"` - commit work to local repo with commit message 'msg'

### Branching

-   `git branch` - list local branches
-   `git branch newBranch` - creates a new branch
-   `git checkout newBranch` - switches to the branch specified


### Remote Repos
* `git remote add alias url` - add `alias` as name for remote repo `url` in project configuration
* `git push alias aBranch` - push local commits to remote repo `alias`'s branch `aBranch`
* `git pull alias aBranch` - pull remote `aBranch` from `alias` into current local branch
