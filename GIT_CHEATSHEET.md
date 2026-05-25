# 🚀 Git & GitHub Cheatsheet

Study these commands to master the basic workflow of version control.

## 1. The Daily Workflow (The "Big Three")
Use these whenever you finish a piece of work.
*   `git add .`  
    *Stages all changes in the current folder.*
*   `git commit -m "Your message"`  
    *Creates a permanent checkpoint (save) with a description.*
*   `git push`  
    *Sends your local checkpoints to GitHub.*

---

## 2. Checking Status
*   `git status`  
    *Shows which files are modified, staged, or untracked (red vs. green).*
*   `git log`  
    *Shows a list of all commits (checkpoints) you've made locally.*

---

## 3. Starting New
*   `git init`  
    *Turns a regular folder into a Git repository.*
*   `git remote add origin <url>`  
    *Connects your local folder to a new GitHub repository.*

---

## 4. Useful Tips
*   `git diff`  
    *Shows the exact line-by-line changes you've made but haven't staged yet.*
*   `git commit --amend -m "new message"`  
    *Fixes the message of your very last commit (if you haven't pushed yet).*

---

## 💡 Pro-Tip for Studying:
Try to run `git status` **between every command**. It's the best way to visualize what Git is doing behind the scenes!
