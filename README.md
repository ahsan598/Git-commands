## GIT COMMANDS!!!

### create a new repository on the command line
- echo "# Git-commands" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin <remote-url>
- git push -u origin main


### push an existing repository from the command line
- git remote add origin <remote-url>
- git branch -M main
- git push -u origin main

### Sub Commands
- git help -a / git help -g             >>>  `git help`

- git status
- git branch / git branch -a
- git branch <brname>
- git checkout <brname>
- git fetch                             >>> `get the updates from git repo`
- git pull                              >>> `get the updates from git repo & merge it locally`
- git remote show origin
- git remote -v
- git remote get-url origin             >>> `to get the origin details and set new origin`
- git remote set-url origin <remote-url>
- git branch -d testfile2				>>>	`deleting branch locally`
- git push origin -d testfile2			>>> `deleteing branch remotely`
- git rm testfile2						>>> `removing file locally`
- git commit -m "remove testfile2"		>>> `removing file remotely`
- git push origin main
- git clone -b <brname> <remote-url>	>>>  `Clone a Specific Branch`



### Core:
• git init
• git clone
• git add
• git commit
• git status
• git diff
• git checkout
• git reset
• git log
• git show
• git tag
• git push
• git pull

### Branching:
• git branch
• git checkout -b
• git merge
• git rebase
• git branch --set-upstream-to
• git branch --unset-upstream
• git cherry-pick

### Merging:
• git merge
• git rebase

### Stashing:
• git stash
• git stash pop
• git stash list
• git stash apply
• git stash drop

### Remotes:
• git remote
• git remote add
• git remote remove
• git fetch
• git pull
• git push
• git clone --mirror

### Configuration:
• git config
• git global config
• git reset config

### Plumbing:
• git cat-file
• git checkout-index
• git commit-tree
• git diff-tree
• git for-each-ref
• git hash-object
• git ls-files
• git ls-remote
• git merge-tree
• git read-tree
• git rev-parse
• git show-branch
• git show-ref
• git symbolic-ref
• git tag --list
• git update-ref

### Porcelain:
• git blame
• git bisect
• git checkout
• git commit
• git diff
• git fetch
• git grep
• git log
• git merge
• git push
• git rebase
• git reset
• git show
• git tag

### Alias:
• git config --global alias.<alias> <command>

### Hook:
• git config --local core.hooksPath <path>

### Additional
• git annex
• git am
• git cherry-pick --upstream
• git describe
• git format-patch
• git fsck
• git gc
• git help
• git log --merges
• git log --oneline
• git log --pretty=
• git log --short-commit
• git log --stat
• git log --topo-order
• git merge-ours
• git merge-recursive
• git merge-subtree
• git mergetool
• git mktag
• git mv
• git patch-id
• git p4
• git prune
• git pull --rebase
• git push --mirror
• git push --tags
• git reflog
• git replace
• git reset --hard
• git reset --mixed
• git revert
• git rm
• git show-branch
• git show-ref
• git show-ref --heads
• git show-ref --tags
• git stash save
• git subtree
• git tag --delete
• git tag --force
• git tag --sign
• git tag -f
• git tag -l
• git tag --verify
• git unpack-file
• git update-index
• git verify-pack
• git worktree