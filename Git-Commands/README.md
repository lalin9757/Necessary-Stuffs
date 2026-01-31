## Table of Contents
- [Create Empty `README.md` inside folder](#create-empty-readme-.md-inside-folder)
  - [Command Prompt (CMD)](#command-prompt-cmd)
  - [Git Bash](#git-bash)
- [Git Commands for Repository Management](#git-commands-for-repository-management)
  - [Initialize Git](#initialize-git)
  - [Add to Staging](#add-to-staging)
  - [Commit Changes](#commit-changes)
  - [Add Remote](#add-remote)
  - [Push Changes](#push-changes)
    - [Initial Push](#initial-push)
    - [Upload Next Changes to GitHub](#upload-next-changes-to-github)
  - [Check Repository Status](#check-repository-status)
  - [Pull Latest Changes](#pull-latest-changes)
  - [Create New Branch](#create-new-branch)
  - [Switch Branches](#switch-branches)
  - [Create and Switch Branch](#create-and-switch-branch)
  - [Merge Branches](#merge-branches)
  - [View Commit History](#view-commit-history)
  - [Clone Repository](#clone-repository)
## Create Empty `README.md` inside folder
### Command Prompt (CMD)
```cmd
nul > README.md
```
### Git Bash
```bash
touch README.md
```
## Git Commands for Repository Management
### Initialize Git
```bash
git init
```
### Add to Staging
```bash
git add .
# or for specific file:
git add README.md
```
### Commit Changes
```bash
git commit -m "Your commit message here"
```
### Add Remote
```bash
git remote add origin YOUR_REMOTE_REPOSITORY_URL
```
### Push Changes
#### Initial Push
```bash
git push -u origin main
# (Note: Default branch might be `master` instead of `main`.)
```
#### Upload Next Changes to GitHub
**Stage Changes:**
```bash
git add .
# or for specific file:
git add <file-name>
```
**Commit Changes:**
```bash
git commit -m "Your descriptive commit message here"
```
**Push to Remote:**
```bash
git push
```
### Check Repository Status
```bash
git status
```
### Pull Latest Changes
```bash
git pull
```
### Create New Branch
```bash
git branch <branch-name>
```
### Switch Branches
```bash
git checkout <branch-name>
```
### Create and Switch Branch
```bash
git checkout -b <new-branch-name>
```
### Merge Branches
```bash
git merge <branch-to-merge>
```
### View Commit History
```bash
git log
```
### Clone Repository
```bash
git clone YOUR_REMOTE_REPOSITORY_URL
```

