# Cursor Setup Assignment

## Objective

This repository documents the completion of a development environment setup assignment. The goal was to install and configure the required tools for modern AI-assisted development, verify that each tool works correctly, and record the steps taken along the way.

## Tools Installed

- **Cursor IDE** — AI-powered code editor
- **Claude Code** — Anthropic's CLI coding assistant
- **OpenAI Codex CLI** — OpenAI's command-line coding tool
- **Git** — Version control system
- **Homebrew** — macOS package manager
- **Node.js** — JavaScript runtime
- **npm** — Node.js package manager

## Steps Completed

1. **Installed Homebrew** — Downloaded and ran the official Homebrew installation script from [brew.sh](https://brew.sh), then verified the installation with `brew --version`.

2. **Installed Git** — Confirmed Git was available on the system (via Xcode Command Line Tools or Homebrew) and verified with `git --version`.

3. **Installed Node.js and npm** — Used Homebrew to install Node.js (`brew install node`), which includes npm. Verified both with `node --version` and `npm --version`.

4. **Installed Cursor IDE** — Downloaded Cursor from the official website, moved it to the Applications folder, and completed the initial setup wizard.

5. **Installed Claude Code** — Followed Anthropic's installation instructions for the Claude Code CLI and authenticated with an API key.

6. **Installed OpenAI Codex CLI** — Installed the Codex CLI tool and configured it with the required credentials.

7. **Verified the environment** — Ran version checks on all tools and confirmed each was accessible from the terminal and ready for use.

## Issues Encountered

- **Homebrew was not installed** — The system did not have Homebrew, which is required to install Node.js and other dependencies on macOS.
- **Node.js and npm were missing** — Neither the Node.js runtime nor the npm package manager was present on the machine.
- **Cursor's interface was different from older tutorials** — Setup guides and video tutorials referenced an older UI layout, making some navigation steps unclear.

## Solutions

- **Homebrew** — Installed Homebrew using the official one-line install command from [brew.sh](https://brew.sh). After installation, added Homebrew to the shell `PATH` as instructed by the installer output.
- **Node.js and npm** — Installed both in a single step via Homebrew (`brew install node`). This resolved the missing runtime and package manager without needing a separate npm install.
- **Cursor UI differences** — Relied on Cursor's in-app onboarding prompts and the latest official documentation rather than outdated tutorials. Used the command palette (`Cmd+Shift+P`) to locate settings and features when the UI did not match older guides.

## What I Learned

- Homebrew is the standard way to install developer tools on macOS and simplifies dependency management.
- Node.js and npm are often installed together; checking for one usually tells you whether both are available.
- Official documentation is more reliable than third-party tutorials, especially for tools that update frequently like Cursor.
- Verifying installations with `--version` flags is a quick way to confirm tools are on the `PATH` and working.
- A structured setup log makes it easier to troubleshoot environment issues later.

## Final Status

All required tools were installed successfully and are ready to use. The development environment is fully configured for AI-assisted coding with Cursor, Claude Code, and OpenAI Codex CLI.
