# 🚀 Git & GitHub A-Z Guide

Welcome to the ultimate Git and GitHub guide! This document explains the basics, key definitions, and essential commands you need to start version-controlling your projects.

---

## 📖 What is Git?

**Git** is a **distributed version control system** that helps developers track and manage changes in their codebase over time.

- ⏳ Track changes
- 👨‍👩‍👧 Collaborate with teams
- 🛠 Restore previous versions

---

## 🌐 What is GitHub?

**GitHub** is a cloud-based platform that hosts Git repositories and provides tools for collaboration.

- ☁️ Stores your Git repositories online
- 🔁 Enables collaboration via **pull requests**
- 🔒 Offers version control, issue tracking, etc.

---

## 🧠 Key Definitions

| Term | Meaning |
|------|---------|
| **Repository (Repo)** | Project folder where code and version history is stored |
| **Commit** | A snapshot of your changes |
| **Branch** | A separate version of your code to work on features independently |
| **Merge** | Combining changes from different branches |
| **Clone** | Downloading a GitHub repo to your local machine |
| **Push** | Sending your code from local to GitHub |
| **Pull** | Fetching latest changes from GitHub to your local repo |
| **Pull Request** | Request to merge your branch into the main repo |
| **Fork** | Copying someone else's repo to your GitHub account |
| **Remote** | The URL of the GitHub repo connected to your local repo |

---

## 💻 Basic Git Setup (One-time)

``` bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```
## Common Git Commands (A-Z)
**📂 A. Initialize Repository**
``` bash

git init
```
**🗃️ B. Add Files to Staging Area**
``` bash

git add filename         # Single file
git add .                # All files
```
**📌 C. Commit Changes**
``` bash

git commit -m "Your message"
```
**🔁 D. Check Status**
``` bash

git status
```
**📚 E. View History**
```bash

git log
```
**🌿 F. Create Branch**
``` bash

git branch new-branch
```
**🔄 G. Switch Branch**
``` bash

git checkout branch-name
```
**🔗 H. Connect to Remote Repository**
```bash

git remote add origin https://github.com/<username>/<repo>.git
```
**🚀 I. Push to GitHub**
```bash

git push -u origin main   # First time
git push                  # Next times
```
**⬇️ J. Pull from GitHub**
```bash

git pull origin main
```
**🔀 K. Merge Branch**
```bash

git checkout main
git merge branch-name
```
**🧹 L. Delete Branch**
```bash

git branch -d branch-name
```
**📥 M. Clone Repo from GitHub**
```bash

git clone https://github.com/user/repo.git
```
**🤝 How to Contribute Using GitHub (Fork → Clone → PR)
Fork the repository**

**Clone it to your machine:**

```bash

git clone https://github.com/your-username/forked-repo.git
Create a new branch:
```
``` bash

git checkout -b my-feature
Make changes, then:
```
``` bash
git add .
git commit -m "Added my feature"
git push origin my-feature
Go to GitHub and open a Pull Request (PR)
```
**🧠 Tips**
- ✅ Always commit with meaningful messages

- 🔀 Pull before push to avoid conflicts

- 🧪 Use branches to test features safely
**✨move from master to main**
- `git branch -m master main ` 


## ❤️ Made for Beginners friendly ##
This guide is designed for learners who want to start using Git and GitHub confidently. Happy coding!



---




