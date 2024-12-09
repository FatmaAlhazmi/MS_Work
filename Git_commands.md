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




## 11. Undo Changes


## 12. View Commit History



## 13. Delete a Branch



## 14. Set Up a .gitignore File




## 15. Check Differences Between Changes


## 16. Common Shortcuts




## Notes:
- Use git status frequently to stay updated on your repository’s state.
- Add meaningful commit messages for better collaboration and tracking.
