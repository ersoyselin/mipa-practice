# MIPA Practice – Git & GitHub Exercises

This repository contains my practice work for Git and GitHub as part of the **Computational Imaging Lab MIPA tutorial**.

The exercises are completed in line with the tutorial provided here:  
[Notebook Preview](https://htmlpreview.github.io/?https://raw.githubusercontent.com/Computational-Imaging-LAB/mipa-practice/master/notebook.html)

---

## 📂 Repository Structure

- `.github/workflows/hello.yml`  
  → Simple GitHub Actions workflow: **Hello World**
- `README.md`  
  → Project summary, instructions, and documentation

---

## 🚀 Exercises Completed

### 1. Git Basics
- Initialized repository
- Made multiple small commits demonstrating Git flow
- Used feature branches effectively (`feature-readme-update`, `conflict-branch`, `add-documentation`)

### 2. Merge Conflicts
- Simulated and resolved merge conflicts between branches
- Practiced `git merge`, `git rebase`, and conflict resolution

### 3. Interactive Rebase
- Squashed multiple commits into one using `git rebase -i HEAD~3`
- Maintained a **clean commit history**

### 4. GitHub Actions
- Created a workflow file: `.github/workflows/hello.yml`
- Verified automation via GitHub Actions tab

### 5. GitHub Issues & Projects
- Created issues with labels
- Created a project board (Kanban)
- Added issues to the project board and tracked progress
- Opened pull requests linked to issues (used `Closes #issue_number`)

### 6. GitHub API Practice
- Generated a Personal Access Token (PAT)
- Fetched repo info using:
  ```bash
  curl -H "Authorization: token <YOUR_TOKEN>" https://api.github.com/repos/ersoyselin/mipa-practice
