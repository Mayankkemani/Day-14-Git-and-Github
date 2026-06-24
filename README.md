# Day 14 - Git Fundamentals 🚀

## Overview

Today I started learning Git, one of the most important tools used in DevOps and software development.

Git helps track changes in files, manage project history, and collaborate efficiently with teams.

---

## Topics Covered

- What is Git?
- Git vs GitHub
- Git Repository
- git init
- git status
- git add
- git commit
- git log
- Working Directory
- Staging Area
- Local Repository

---

# What is Git?

Git is a Distributed Version Control System (VCS).

It helps developers:

- Track code changes
- Manage project history
- Collaborate with teams
- Restore previous versions

---

# Git vs GitHub

## Git

```text
Version Control System
Runs on Local Machine
Tracks File Changes
```

## GitHub

```text
Cloud Platform
Hosts Git Repositories
Used for Collaboration
```

Easy Example:

```text
Git     = Notebook

GitHub  = Google Drive
```

---

# Creating a Git Repository

Create Project:

```bash
mkdir git-practice

cd git-practice
```

Initialize Git:

```bash
git init
```

Output:

```text
Initialized empty Git repository
```

---

# Checking Repository Status

Command:

```bash
git status
```

Purpose:

```text
Shows:
- Modified Files
- Untracked Files
- Staged Files
```

---

# Adding Files to Staging Area

Add Specific File:

```bash
git add file.txt
```

Add All Files:

```bash
git add .
```

---

# Creating First Commit

Command:

```bash
git commit -m "First Commit"
```

Purpose:

```text
Saves changes into Git history
```

---

# Viewing Commit History

Command:

```bash
git log

git log --oneline
```

Purpose:

```text
View previous commits
Track project history
```

---

# Understanding Git Workflow

```text
Working Directory
       ↓
git add
       ↓
Staging Area
       ↓
git commit
       ↓
Local Repository (.git)
       ↓
git push
       ↓
GitHub
```

---

# Practical Work Done

Today I:

✅ Initialized a Git Repository

✅ Checked Repository Status

✅ Added Files to Staging Area

✅ Created My First Commit

✅ Viewed Commit History

✅ Learned About Git Internal Storage (.git Folder)

---

# Real Repository Practice

Repository:

```text
test/
```

Commit Created:

```text
my 50+ scripts add to git
```

Git Statistics:

```text
42 Files Changed

734 Insertions
```

---

# Key Learnings

✅ Git is a Version Control System

✅ Git and GitHub are different

✅ Git stores history inside the .git folder

✅ git add moves files to staging area

✅ git commit saves changes permanently

✅ git log shows commit history

✅ Git works locally without internet

---

# DevOps Roadmap Progress

```text
✅ Linux Fundamentals

✅ Bash Scripting

✅ 50+ Automation Scripts

✅ Networking Fundamentals

✅ Advanced Networking Concepts

✅ Git Fundamentals

🔜 GitHub

🔜 Docker

🔜 CI/CD (Jenkins & GitHub Actions)

🔜 AWS

🔜 Kubernetes

🔜 Terraform

🔜 Prometheus

🔜 Grafana
```

# Day 14 Complete 🚀
