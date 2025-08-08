# Demo DevOps Project

## Overview
This is a simple demo project to showcase best practices for managing a DevOps project with Git version control.

## Branching Strategy
- **main**: Production-ready code
- **dev**: Development integration branch
- **feature/***: Feature branches for individual tasks

## Workflow
1. Create a feature branch from `dev`
2. Commit and push your changes
3. Open a Pull Request (PR) from your feature branch to `dev`
4. After review, merge the PR
5. When features are ready, open a PR from `dev` to `main`
6. Tag releases on `main` (e.g., v1.0)

## How to Run
Simply open `index.html` in a web browser.

## .gitignore
This repo ignores log files and OS-specific files.

## Tags
Releases are tagged on the `main` branch to mark important versions.

---

Created for Git version control learning purposes.

