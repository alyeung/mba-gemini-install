# MBA Gemini Install

Project notes for local Gemini CLI setup and experimentation on macOS.

## Installation Notes

These notes assume you are using a Mac.

### 1. Open the Homebrew Website

Go to the official Homebrew website:

<https://brew.sh/>

### 2. Install Homebrew

Homebrew is a package manager for macOS. It helps install and manage developer tools from the command line.

Install Homebrew using the current command from the official Homebrew site:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Source: <https://brew.sh/>

### 3. Install Gemini CLI

The Gemini CLI documentation lists Homebrew as a recommended installation method for macOS/Linux.

```sh
brew install gemini-cli
```

Source: <https://geminicli.com/docs/get-started/installation/#install-gemini-cli>

### 4. Install Python

Python is a programming language used by developers. Gemini can use Python to take actions on files and automate local tasks.

Use Homebrew to install Python:

```sh
brew install python
```

### 5. Run Gemini CLI

After installation, start Gemini CLI with:

```sh
gemini
```

### 6. Authenticate Gemini CLI

Gemini CLI needs to authenticate before it can be used. Follow the sign-in or authentication prompts that appear after starting Gemini CLI.

You can log in with your UC Berkeley Google account.

## Requirements Mentioned in the Docs

- macOS 15+
- Node.js 20.0.0+
- Bash, Zsh, or PowerShell
- Internet connection
