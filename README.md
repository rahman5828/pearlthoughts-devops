# Day 1 – Task 1: Gitea Local Setup

## Objective

Set up Gitea locally from source, build and run the Gitea server, configure SQLite3, create an administrator account, and verify the application through the web interface.

## Environment

- OS: macOS ARM64
- Go: 1.27.0
- Node.js: 26.7.0
- pnpm: 11.22.0
- Make: 3.81
- Git LFS: 3.7.1
- Database: SQLite3
- Gitea: 1.28.0+dev-408-g9eb4a9afad

## Setup

### 1. Clone Repository

```bash
git clone https://github.com/go-gitea/gitea.git
cd gitea
