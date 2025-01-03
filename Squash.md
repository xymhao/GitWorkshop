
# Git Squash - Combine Multiple Commits

`git squash` is used to combine multiple commits into a single commit, making the commit history cleaner and more concise. It is typically done with `git rebase -i`.

## Steps:

1. **Start interactive rebase**:

git rebase -i HEAD~3

2. **Edit commit commands**: Change `pick` to `squash` (or `s`) for the commits you want to combine.

```text
pick abc123 Commit 1
squash def456 Commit 2
squash ghi789 Commit 3