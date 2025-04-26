# Learn about Git repositories, what they are, and how to work with commits
## What is a Git Repository?
A **Git repository** is like a **project folder** that Git is tracking.

It holds your project's files, **plus** a hidden .git folder where Git stores all **versions** and **history** of your project.

Repositories can be:

**Local** (on your machine)

**Remote** (on platforms like GitHub, GitLab, Bitbucket)

## 🛠️ How to Create and Work with a Repository:

### 1.Create a New Repository:
In your project folder:
```js
bash git init
```
This sets up the .git directory and makes it a Git repository.

### 2.Clone an Existing Repository (from GitHub, etc.):

Example:
```js
bash
git clone https://github.com/username/repo-name.git
```
This copies the remote project to your machine.

### 📝 What is a Git Commit?
*  A **commit** is like a **snapshot** of your project at a specific point.

It saves **what has changed** — your updates, new files, deletions, etc.

Each commit has:

A unique ID (hash)

Author info

Date/time

A message describing the changes


