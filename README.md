# PearlThoughts DevOps – Day 1 Task 1

## Task: Gitea Setup and Repository Management

This submission demonstrates the setup and usage of a self-hosted Gitea instance for Git repository management.

## Environment

- OS: macOS
- Git: Git CLI
- Repository Platform: Gitea
- Gitea URL: http://localhost:3000
- Repository: pearlthoughts-devops
- Branch: main

## Work Completed

- Set up Gitea locally
- Started and accessed the Gitea web interface
- Created a repository in Gitea
- Configured Git remote
- Pushed repository content to Gitea
- Verified the repository through the Gitea web interface

## Repository

Gitea repository:

`http://localhost:3000/abdulrahman/pearlthoughts-devops`

## Git Commands Used

```bash
git init
git branch -M main
git remote add gitea http://localhost:3000/abdulrahman/pearlthoughts-devops.git
git push -u gitea main
