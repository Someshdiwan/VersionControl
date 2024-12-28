# Git Command Roadmap 🚀

It’s a perfect reference for both beginners and advanced Git users looking to enhance their understanding of version control.

---

## 1. Core Commands

### `git init`
Initializes a new Git repository.

### `git clone`
Clones a repository into a newly created directory.

### `git add`
Adds changes in the working directory to the staging area.

### `git commit`
Records the changes in the repository.

### `git status`
Displays the state of the working directory and the staging area.

### `git diff`
Shows the changes between commits, commit and working tree, etc.

### `git checkout`
Switches between branches or restores working directory files.

### `git reset`
Resets current HEAD to a specified state.

### `git log`
Shows the commit logs.

### `git show`
Shows various types of objects like commits, trees, and blobs.

### `git tag`
Creates, lists, deletes, or verifies tags in Git.

### `git push`
Updates remote references along with associated objects.

### `git pull`
Fetches from and integrates with another repository or a local branch.

---

## 2. Branching

### `git branch`
Lists, creates, or deletes branches.

### `git checkout -b`
Creates a new branch and switches to it.

### `git merge`
Joins two or more development histories together.

### `git rebase`
Reapplies commits on top of another base tip.

### `git cherry-pick`
Applies the changes introduced by some existing commits.

---

## 3. Merging

### `git merge`
Incorporates changes from named commits into the current branch.

### `git rebase`
Reapplies commits on top of another base tip.

---

## 4. Stashing

### `git stash`
Saves the working directory and index state.

### `git stash pop`
Restores previously stashed changes.

### `git stash apply`
Applies a stash to your working directory.

### `git stash drop`
Discards the most recently stashed changes.

---

## 5. Remotes

### `git remote`
Manages remote repository connections.

### `git push`
Pushes the committed changes to a remote repository.

### `git pull`
Fetches changes from a remote repository and merges them.

### `git fetch`
Downloads objects and refs from another repository.

---

## 6. Configuration

### `git config`
Sets Git configuration values.

### `git global config`
Sets global Git configuration values.

### `git reset config`
Resets configuration settings in Git.

---

## 7. Plumbing Commands

These are low-level commands used internally by Git, but available for users if needed.

### `git cat-file`
Provides content or type and size information for repository objects.

### `git ls-files`
Shows information about files in the index and the working tree.

... and more.

---

## 8. Porcelain Commands

These are user-friendly commands for everyday Git operations.

### `git blame`
Shows what revision and author last modified each line of a file.

### `git bisect`
Finds the commit that introduced a bug by binary search.

---

## 9. Alias Setup

### `git config --global alias.<alias> <command>`
Creates a shortcut for commonly used commands.

---

## 10. Hooks Configuration

### `git config --local core.hooksPath <path>`
Sets the path for hooks directory.

---

## 11. Experimental Commands

Commands that are in development or may not be fully supported.

### `git annex`
Manages large files with Git.

### `git pull --rebase`
Fetches changes and re-applies commits on top of the fetched branch.

---

## Contributing

1. Fork this repository
2. Create a new feature branch (`git checkout -b feature/NewFeature`)
3. Commit your changes (`git commit -m "Added a new feature"`)
4. Push to the branch (`git push origin feature/NewFeature`)
5. Open a pull request

