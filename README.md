# TestWorkTree
This Repo is used to Test the Git WorkTree command, explained in this blogpost:

https://andrewlock.net/working-on-two-git-branches-at-once-with-git-worktree

## Setup a new worktree

git worktree add ../TestWorkTree-2nd-WT origin/master

This command creates a new worktree based on the origin/master branch

## Removing the worktree

git worktree remove ../TestWorkTree-2nd-WT

This command deletes the created worktree
