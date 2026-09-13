# Termux

This repository contains my Termux practice and projects.

## What I am learning
- Git & GitHub
- Linux/Termux commands
- C/C++
- Java
- SQL

## Author
Adarsh# Termux

Termux — Git & GitHub Practice Repository

A hands-on repository for learning Termux, Git, GitHub, version control, and collaborative development workflows.

This repository is mainly used to practice real-world development workflows directly from the Termux terminal on Android.

---

🎯 Purpose

The goal of this repository is to build practical experience with:

- Linux/Termux commands
- Git fundamentals
- GitHub repository management
- Branch-based development
- Issues and issue tracking
- Pull Requests (PRs)
- Commits and commit history
- Remote repositories
- Collaboration workflows
- Debugging and fixing code through GitHub Issues

---

🛠️ Tools & Technologies

Tool| Purpose
Termux| Linux-like development environment on Android
Git| Version control
GitHub| Remote repository and collaboration
GitHub CLI ("gh")| Manage GitHub directly from Termux
Shell| Terminal commands and automation
Java / C / SQL| Programming practice

---

📚 Git & GitHub Practice

This repository covers the complete basic GitHub workflow.

1. Repository Setup

git init
git remote add origin <repository-url>
git remote -v

2. Check Repository Status

git status

3. Add Changes

git add .

or:

git add <filename>

4. Commit Changes

git commit -m "Describe your change"

5. Push to GitHub

git push

6. Pull Latest Changes

git pull

---

🌿 Branch Workflow

Changes are developed on separate branches instead of directly modifying "main".

Example:

git checkout -b issue-1-division

Make the required changes, then:

git add .
git commit -m "Fix division issue"
git push -u origin issue-1-division

After testing the changes, a Pull Request can be created to merge the branch into "main".

---

🐛 Issues

GitHub Issues are used to track bugs, improvements, and tasks.

Example workflow:

Issue
  ↓
Create a branch
  ↓
Make changes
  ↓
Commit changes
  ↓
Push branch
  ↓
Create Pull Request
  ↓
Review
  ↓
Merge

Example Issue

Issue #1 — Division by Zero

Problem:
The program does not properly handle division by zero.

Solution:
Add validation before performing the division operation.

---

🔀 Pull Requests

Pull Requests are used to propose changes from a feature/fix branch into "main".

Using GitHub CLI:

gh pr create \
  --title "Fix division issue" \
  --body "Resolved issue #1"

A Pull Request can then be reviewed and merged through GitHub.

---

🔗 GitHub CLI

GitHub CLI allows GitHub operations directly from Termux.

Check installation:

gh --version

Authenticate:

gh auth login

Check authentication:

gh auth status

Useful commands:

gh repo view
gh issue list
gh issue create
gh issue close <issue-number>
gh pr list
gh pr create
gh pr view
gh pr checkout <pr-number>
gh pr merge

---

🧪 Current Practice Workflow

The repository is being used to practice a realistic development cycle:

GitHub Issue
     ↓
Create Branch
     ↓
Write / Fix Code
     ↓
Test Locally
     ↓
git add
     ↓
git commit
     ↓
git push
     ↓
Create Pull Request
     ↓
Review Changes
     ↓
Merge into main

---

📁 Repository Structure

The structure may evolve as new concepts and projects are added.

Termux/
│
├── README.md
├── programs/
├── java/
├── c/
├── sql/
└── practice/

---

🎓 Learning Objectives

By working on this repository, I aim to become comfortable with:

- Command-line development
- Git version control
- GitHub collaboration
- Branch management
- Issue tracking
- Pull Request workflow
- Debugging through version control
- Writing meaningful commit messages
- Working with remote repositories
- Understanding professional development workflows

---

🚀 Future Improvements

Planned additions include:

- More programming exercises
- Java projects
- C/C++ practice
- SQL/DBMS practice
- Shell scripting
- Git branching experiments
- More GitHub Issues
- Pull Request reviews
- GitHub Actions / CI
- Better project organization

---

👨‍💻 Author

Adarsh

Student | Computer Science & Engineering

Learning by building, experimenting, debugging, and using real development workflows.

---

⭐ Repository Status

Learning & Practice Repository

This repository is continuously evolving as new programming, Git, GitHub, and development concepts are learned and practiced.
