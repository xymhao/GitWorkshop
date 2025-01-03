# Git Basic Commands

# 1. Configure Git
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# 2. Create a Git Repository
git init

# 3. Clone a Remote Repository
git clone <repository_url>

# 4. Check Repository Status
git status

# 5. Track Files
git add <file_name>
git add .  # Add all files

# 6. Commit Changes
git commit -m "Commit message"

# 7. View Commit Log
git log

# 8. View File History
git log <file_name>

# 9. Create a New Branch
git branch <branch_name>
git checkout <branch_name>
# Or
git checkout -b <branch_name>

# 10. Merge Branches
git merge <branch_name>

# 11. Delete a Branch
git branch -d <branch_name>

# 12. Push to Remote Repository
git push origin <branch_name>

# 13. Pull Updates from Remote Repository
git pull origin <branch_name>

# 14. Fetch Updates from Remote Repository
git fetch origin

# 15. View Remote Repository
git remote -v

# 16. Set Remote Repository
git remote add origin <repository_url>

# 17. Remove Remote Repository
git remote remove origin

# 18. View Branches
git branch

# 19. Reset File Changes
git checkout -- <file_name>

# 20. Discard Local Commits
git reset --hard <commit_hash>
