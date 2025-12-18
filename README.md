# AI-Ml
This is my First project in Github.
<br>
Author: Akshay 
Github Commands
<br>
Here is a **clear, beginner-friendly list of essential GitHub (Git) commands**, from **basic → advanced**, with **simple explanations** and examples.

---

# 🔧 GitHub / Git Commands Cheat Sheet

> **Git** = version control tool
> **GitHub** = online platform to store Git repositories

---

## 🚀 1. Basic Setup (One-time)

```bash
git --version
```

Check Git installation

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@gmail.com"
```

Set username & email

```bash
git config --list
```

View configuration

---

## 📁 2. Repository Creation

### Create new local repo

```bash
git init
```

### Clone existing repo

```bash
git clone https://github.com/username/repo-name.git
```

---

## 📊 3. Basic Daily Commands (MOST IMPORTANT)

### Check status

```bash
git status
```

### Add files

```bash
git add file.txt
git add .
```

### Commit changes

```bash
git commit -m "Initial commit"
```

### View commit history

```bash
git log
git log --oneline
```

---

## ☁️ 4. Remote Repository (GitHub)

### Add remote repo

```bash
git remote add origin https://github.com/username/repo-name.git
```

### Push code to GitHub

```bash
git push origin main
```

### Pull latest code

```bash
git pull origin main
```

---

## 🌿 5. Branching Commands

### List branches

```bash
git branch
```

### Create new branch

```bash
git branch feature1
```

### Switch branch

```bash
git checkout feature1
```

(or)

```bash
git switch feature1
```

### Create + switch

```bash
git checkout -b feature1
```

---

## 🔀 6. Merge Branches

```bash
git checkout main
git merge feature1
```

---

## ⚠️ 7. Undo / Fix Mistakes

### Undo staged file

```bash
git reset file.txt
```

### Undo last commit (keep changes)

```bash
git reset --soft HEAD~1
```

### Discard local changes

```bash
git checkout -- file.txt
```

---

## 🔥 8. Stash (Temporary Save)

```bash
git stash
git stash list
git stash apply
```

---

## 🔐 9. Authentication (Modern GitHub)

```bash
git push https://github.com/username/repo.git
```

Use:

* GitHub **Personal Access Token** instead of password

---

## 📦 10. Advanced Commands

### Rebase

```bash
git rebase main
```

### Cherry-pick

```bash
git cherry-pick commit_id
```

### Tag

```bash
git tag v1.0
git push origin v1.0
```

---

## 🧠 11. Git Workflow (Simple)

```text
Working Directory → Staging → Commit → Push
```

Commands flow:

```bash
git add .
git commit -m "message"
git push
```

---



