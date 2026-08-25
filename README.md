# Day 1 – Task 1: Gitea Local Setup

## Objective

Set up Gitea locally from source, configure it to use SQLite3, build and run the Gitea server, create an administrator account, and verify that the application is running successfully through the web interface.

---

## Environment

- **Operating System:** macOS
- **Architecture:** ARM64
- **Version Control:** Git
- **Application:** Gitea
- **Database:** SQLite3
- **Build Tool:** Make
- **Runtime:** Go
- **Package Manager:** Homebrew
- **Git LFS:** Git LFS
- **Repository:** Gitea

---

## 1. Clone the Gitea Repository

The Gitea source code was cloned from the official Gitea repository.

```bash
git clone https://github.com/go-gitea/gitea.git
cd gitea
