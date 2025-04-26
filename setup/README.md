.
#  Install and configure Git on your local machine
## 🖥️ For Windows:
###  1. Download and Install Git:
Go to https://git-scm.com/download/win

The download should start automatically.

Run the installer and accept the default settings (unless you have specific preferences).

### 2. Verify Installation:
Open Git Bash or Command Prompt, then type:
```js
bash
git --version
```
### 3. Configure Git:
Run the following commands (replace with your details):
```js
bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
## 🍎 For macOS:
### 1. Install Git:
Option 1 – via Homebrew (recommended):
```js
bash
brew install git
```
 Option 2 – via Xcode Command Line Tools:
```js
bash

xcode-select --install
```
### 2. Verify Installation:
```js
bash
git --version
```
### 3. Configure Git:
```js
bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
## 🐧 For Linux (Ubuntu/Debian):
### 1. Install Git:
```js
bash
sudo apt update
sudo apt install git
```
### 2. Verify Installation:
```js
bash
git --version
```
### 3. Configure Git:
```js
bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
## ✅ Optional (but useful):
Set your default branch name:

```js
bash
git config --global init.defaultBranch main
```
Enable colored output:

```js
bash
git config --global color.ui auto
```
Check current configuration:
```js
bash
git config --list
```
Would you like help setting up SSH keys for GitHub/GitLab too?















