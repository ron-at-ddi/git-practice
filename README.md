# Practice repository to start learning Git

## Commands used

- git init: Create a new repository
- git status: Compare working directory, staging area,and current branch
- git add: Add changes from working directory to staging area
- git commit: Commit changes from staging area to current branch
- git config: Set or get configuration
- git log: Show a history (aka "log") of project commmits
- git log branch1..branch2: Log of commits in branch2 that don't exist in branch1
- git log branch1...branch2: Log of commits in either branch but not both
- git show: Show a single commit
- git diff: Show the difference between commits, the working directory, and the staging area
- git checkout: check out branch (update HEAD and apply changes to working directory)
- git branch -c: Create a branch
- git checkout -b: Create branch, then check it out
- bit branch: Shows branches and which one you are currently on
- git merge: Merge changes from different branches
- git merge --abort: Abort an in-progress merge
- git merge --no-commit --no-ff: Attempt to merge, but don't creat auto merge or ff merge
- git branch --no-merged branch1: List branches that have unmerged commits
- git mranch --merged branch1: List branches that have no unmerged commits
- git stash: Stash changes from working directory
- git stash list: List stashes
- git stash pop: Apply stashed changes to working directory


## Merge

# Merging means to bring the changes from one branch into another

- A fast-forward merge happens when the target branch was branched from the current one, and there are no new changes to the current branch since then.

- An automatic merge happens when the two histories have diverged, but git is able to reconcile them into one set of changes. This creates a new commit on the current branch.


