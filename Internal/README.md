# Learn how Git stores data on the files system and the plumbing commands that make it all work

## 🧠 How Git Actually Stores Data
### 1. Git thinks in snapshots, not differences
* Unlike older systems (like SVN) that track **file differences**, Git saves a **full snapshot** of your project **at each commit.**

* If a file hasn’t changed, Git doesn’t store it again — it just links to the previous identical file.

# 📂 What's inside the .git/ folder?
When you run ```git init```, Git creates a ```.git/``` directory with important subfolders:




| Folder/File  | Purpose |
| ------------- |:-------------:|
| ```objects/```.    | Stores all your data (commits, trees, blobs) as compressed files|
| ```refs/	```      | Stores pointers to commits (branches, tags)     |
| ```HEAD```         |    Tells Git which branch you're currently on     |
| ```config```       | Project-specific configuration     |
| ```index	```      | Staging area (what will be in your next commit)   |



# 🧩 Git's Core Building Blocks

**1.Blob** (binary large object):

* Stores file contents.

* No filenames, just data.

**2.Tree:**

* Stores filenames, permissions, and links blobs (and other trees).

* Represents a directory.

**3.Commit:**

* Points to a tree.

* Contains metadata: message, author, parent commits.

**4.Tag:**

* A label for a specific commit.

* **➡️ Think of it like:**
Commit → Tree → Blobs and sub-Trees.

# 🛠️ "Plumbing" Commands
These are **low-level Git commands** (used internally) — not the "porcelain" user-friendly ones like ```git add``` or ``git commit.``






