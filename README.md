# Server Performance Stats Script

[A roadmap.sh project](https://roadmap.sh/projects/server-stats)

This script analyzes basic server performance statistics on a Linux server

## Features

- **Total CPU usage**
- **Total memory usage** (Free vs. Used, including percentage)
- **Total disk usage** (Free vs. Used, including percentage)
- **Top 5 processes by CPU usage**
- **Top 5 processes by memory usage**

## Stretch Goals

Optional additional stats:
- OS version
- Uptime
- Load average
- Logged-in users
- Failed login attempts

## Prerequisites

- Linux operating system
- Bash shell
- Git installed

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/server-performance-stats.git

Navigate to the project directory:
cd server-performance-stats

Make the script executable:
chmod +x server-stats.sh

Run the script:
./server-stats.sh

Commit your changes with a descriptive message:
git commit -m "Add English instruction file in docs/README.md"

Push your changes to the remote repository:
git push

If prompted for authentication, ensure you're using an SSH key or a Personal Access Token instead of your password

Using a Personal Access Token (PAT)
Generate a PAT on GitHub

Go to GitHub PAT settings.
Click "Generate new token".
Set the scopes (permissions) needed, typically "repo".
Generate and copy the token.
Use PAT When Prompted for Password

When Git prompts for a password during git push, paste your PAT instead of your password.

