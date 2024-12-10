# Git Tutorial for macOS and Linux

Git is a version control system used to track changes, collaborate, and manage code. Below is a general guide covering essential Git commands for macOS and Linux users.

---

## 1. Setup Git for the First Time
```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

Check your Git configuration:
```bash
git config --list
```

## 2. Initialize a New Repository
```bash
git init
```

## 3. Clone an Existing Repository
```bash
git clone <repository-link>
```

## 4. Check the Status of Your Repository
```bash
git status
```

## 5. Stage Changes for Commit

Add specific files:
``` bash
git add <file-name>
```

Add all files:
```bash
git add .
```

## 6. Commit Changes
```bash
git commit -m "Your commit message"
```

## 7. Push Changes to a Remote Repository
```bash
git push origin <branch-name>
```

## 8. Pull Changes from a Remote Repository
```bash
git pull origin <branch-name>
```

## 9. Create and Switch to a New Branch

Create a branch:
```bash
git branch <branch-name>
```

Switch to a branch:
```bash
git checkout <branch-name>
```

Create and switch in one step:
```bash
git checkout -b <branch-name>
```


## 10. Merge Branches
```bash
git merge <branch-name>
```


## 11. Undo Changes
Unstage a file:
```bash
git reset <file-name>
```

Discard changes in a file:
```bash
git checkout -- <file-name>
```



## 12. View Commit History
View full history:
```bash
git log
```

View a simplified history:
```bash
git log --oneline
```



## 13. Delete a Branch
Delete a branch locally:
```bash
git branch -d <branch-name>
```

Force delete a branch:
```bash
git branch -D <branch-name>
```

## 14. Set Up a .gitignore File
Create a .gitignore file:
```bash
touch .gitignore
```

Add files or folders to exclude manually by editing .gitignore.

## 15. Check Differences Between Changes
View unstaged changes:
```bash
git diff
```

Compare two commits:
```bash
git diff <commit-id-1> <commit-id-2>
```

## 16. Common Shortcuts
Add and commit in one step:
```bash
git commit -am "Your commit message"
```

Check the current branch:
```bash
git branch
```

Check logs with a graph:
```bash
git log --oneline --graph --all
```

## Notes:
- Use git status frequently to stay updated on your repository’s state.
- Add meaningful commit messages for better collaboration and tracking.
