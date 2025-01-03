# Git Stash - Temporarily Save Changes

`git stash` allows you to temporarily save your work-in-progress (including changes in the working directory and staging area) to a stack, so you can switch to other tasks. You can later retrieve these changes when needed.

## Common Commands

- **View all stashed changes**:

  ```bash
  git stash list


##  Restore the most recent stashed change (and remove it from the stack)
git stash pop

## Restore stashed changes but keep them in the stack
git stash apply

## Delete a specific stash
git stash drop

## Create a new branch and apply the stashed changes
git stash branch <branch_name>