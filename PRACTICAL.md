# Practical: Git Collaboration – Branches, Pull Requests and AI-Assisted Code Reviews

## Aim
To demonstrate Git and GitHub collaboration by creating a feature branch, committing code, opening a Pull Request, reviewing changes, and merging the branch.

## Requirements
- Git
- Visual Studio Code
- GitHub account
- Web browser
- An AI coding assistant for review suggestions

## Concepts
- **Git:** Distributed version control system used to track source-code changes.
- **GitHub:** Platform for hosting Git repositories and collaborating.
- **Branch:** Independent line of development used to work on a feature.
- **Commit:** Recorded snapshot of repository changes.
- **Pull Request (PR):** Proposal to merge changes from one branch into another.
- **AI-assisted review:** Use of an AI assistant to identify possible bugs, accessibility concerns, and maintainability improvements.

## Work performed
1. Created the GitHub repository `AI-Web-Development`.
2. Added this README on the `main` branch.
3. Created the `feature/homepage` branch from `main`.
4. Added `index.html` containing a responsive HTML homepage.
5. Added `AI_CODE_REVIEW.md` documenting review findings and a reusable AI prompt.
6. Prepared the feature branch for a Pull Request into `main`.

## Git commands
```bash
git --version
git clone https://github.com/muditgupta271-ux/AI-Web-Development.git
cd AI-Web-Development
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
git checkout -b feature/homepage
git status
git add .
git commit -m "Add homepage"
git push -u origin feature/homepage
git checkout main
git pull origin main
```

## Pull Request workflow
- Base branch: `main`
- Compare branch: `feature/homepage`
- Review the changed files and discuss any suggested improvements.
- Merge the PR after review.

## AI code-review prompt
Review the HTML file for correctness, accessibility, responsive design, maintainability, and HTML best practices. Report concrete findings with severity and minimal suggested fixes. Do not invent issues.

## Result
The repository demonstrates the core collaboration workflow: a main branch, a feature branch, commits, a proposed Pull Request, and documented AI-assisted review.
