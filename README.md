# Day11

## 📅 Day 11 - Git & GitHub

Today’s Focus:
- Git basics: init, add, commit, status, log
- Branching: `git branch`, `git checkout -b`
- Remote repo setup: `git remote add origin`
- Push & pull changes via GitHub
- Merge conflicts & `.gitignore`

## 📘 Day 11 of #100DaysOfCode – Git & GitHub Mastery

### 🔧 What I Learned Today:

#### ✅ Git Basics
```bash
git init                    # Initialize a new Git repo
git add .                  # Stage all changes
git commit -m "message"    # Save changes with a message
git status                 # Check status of working directory
git log                    # View commit history
git branch dev             # Create a branch
git checkout dev           # Switch to branch
# OR
git checkout -b dev        # Create and switch in one step
git merge dev              # Merge dev into current branch
git remote add origin <repo-url>  # Connect local to GitHub
git push -u origin main           # Push changes to GitHub
git pull origin main              # Pull latest from GitHub
node_modules/
.env
*.log
.DS_Store
