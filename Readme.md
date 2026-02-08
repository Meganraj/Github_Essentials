# GitHub Essentials – Hands-on Commands Guide

***This README contains all the Git & GitHub commands covered during the workshop,  
with **clear explanations and real-time examples** for beginners.***
---


---

## 1. git init
```bash
git init
````

Initializes a new Git repository in the current directory.
Starts tracking changes for the project.

**Real-time example:**
Starting Git tracking for a new college mini-project folder.

---

## 2. git clone

```bash
git clone https://github.com/user/repo.git
```

Creates a local copy of an existing repository.
Used to download projects from GitHub.

**Real-time example:**
Cloning a team project to work on it locally.

---

## 3. git status

```bash
git status
```

Shows the current state of the working directory.
Displays modified, staged, and untracked files.

**Real-time example:**
Checking which files you changed before committing.

---

## 4. git add

```bash
git add file.txt
```

Adds file changes to the staging area.
Prepares files to be committed.

**Real-time example:**
Adding only `index.html` after editing it.

---

## 5. git commit

```bash
git commit -m "Added login page"
```

Saves staged changes to Git history.
Each commit records a snapshot of the project.

**Real-time example:**
Saving completed work at the end of the day.

---

## 6. git config

```bash
git config --global user.name "Your Name"
git config --global user.email "email@example.com"
```

Sets user identity for commits.
Helps identify who made each change.

**Real-time example:**
Configuring Git after first installation.

---

## 7. git log

```bash
git log
```

Displays the commit history of the repository.
Used to review past changes.

**Real-time example:**
Checking when a feature was added.

---

## 8. git show

```bash
git show <commit-id>
```

Shows details of a specific commit.
Includes code changes and author info.

**Real-time example:**
Reviewing what exactly changed in a commit.

---

## 9. git diff

```bash
git diff
```

Shows differences between file versions.
Used before committing changes.

**Real-time example:**
Comparing current changes with the last commit.

---

## 10. git reset

```bash
git reset HEAD file.txt
```

Removes files from the staging area.
Keeps the file changes intact.

**Real-time example:**
Unstaging a file added by mistake.

---

## 11. git branch

```bash
git branch feature-login
```

Creates a new branch.
Allows working on features independently.

**Real-time example:**
Creating a branch for a new feature.

---

## 12. git checkout

```bash
git checkout feature-login
```

Switches to another branch.
Also used to restore files.

**Real-time example:**
Moving from main branch to feature branch.

---

## 13. git switch

```bash
git switch main
```

Switches between branches.
Simpler alternative to git checkout.

**Real-time example:**
Returning to main branch after testing.

---

## 14. git merge

```bash
git merge feature-login
```

Combines changes from one branch into another.
Used after feature completion.

**Real-time example:**
Merging a completed feature into main branch.

---

## 15. git rebase

```bash
git rebase main
```

Moves commits to a new base.
Keeps commit history clean.

**Real-time example:**
Updating your branch with latest main changes.

---

## 16. git cherry-pick

```bash
git cherry-pick <commit-id>
```

Applies a specific commit to current branch.
Used when only one change is required.

**Real-time example:**
Picking a bug-fix commit from another branch.

---

## 17. git remote add

```bash
git remote add origin https://github.com/user/repo.git
```

Connects local repository to GitHub.
Enables push and pull operations.

**Real-time example:**
Linking a local project to GitHub.

---

## 18. git remote -v

```bash
git remote -v
```

Displays connected remote URLs.
Used to verify remote configuration.

**Real-time example:**
Checking if the repo is linked correctly.

---

## 19. git push

```bash
git push origin main
```

Uploads local commits to GitHub.
Shares work with others.

**Real-time example:**
Submitting project code to GitHub.

---

## 20. git pull

```bash
git pull origin main
```

Fetches and merges changes from remote.
Keeps local repo updated.

**Real-time example:**
Getting teammate’s latest changes.

---

## 21. git fetch

```bash
git fetch origin
```

Downloads changes without merging.
Safe way to check updates.

**Real-time example:**
Reviewing changes before merging.

---

## 22. git stash

```bash
git stash
```

Temporarily saves uncommitted changes.
Used before switching branches.

**Real-time example:**
Pausing work to fix urgent issue.

---

## 23. git stash list

```bash
git stash list
```

Shows all saved stashes.
Helps track temporary work.

**Real-time example:**
Checking stashed work from yesterday.

---

## 24. git stash pop

```bash
git stash pop
```

Applies and removes latest stash.
Restores saved changes.

**Real-time example:**
Continuing paused development work.

---

## 25. git clean

```bash
git clean -f
```

Deletes untracked files.
Keeps repository clean.

**Real-time example:**
Removing unwanted temp files.

---

## 26. git tag

```bash
git tag -a v1.0 -m "Release 1.0"
```

Creates a version label.
Used to mark releases.

**Real-time example:**
Tagging first project release.

---

## 27. git tag -d

```bash
git tag -d v1.0
```

Deletes a local tag.
Used to correct tagging mistakes.

**Real-time example:**
Removing wrong version tag.

---

## 28. git push --tags

```bash
git push origin --tags
```

Pushes all tags to GitHub.
Shares release versions.

**Real-time example:**
Publishing release tags online.

---

## 29. git bisect

```bash
git bisect start
```

Finds the commit that introduced a bug.
Uses binary search through commits.

**Real-time example:**
Identifying which commit broke the app.

---

## 30. git blame

```bash
git blame file.txt
```

Shows who modified each line of a file.
Useful for debugging.

**Real-time example:**
Finding who changed a config value.

---

## 31. git reflog

```bash
git reflog
```

Shows all reference updates.
Helps recover lost commits.

**Real-time example:**
Restoring a deleted branch.

---

## 32. git submodule

```bash
git submodule add <repo-url>
```

Adds another repo inside current repo.
Used to manage dependencies.

**Real-time example:**
Adding a shared library project.

---

## 33. git archive

```bash
git archive --format=zip HEAD > project.zip
```

Creates a zip of source code.
Does not include Git history.

**Real-time example:**
Submitting project as ZIP file.

---

## 34. git gc

```bash
git gc
```

Cleans unnecessary Git files.
Improves performance.

**Real-time example:**
Optimizing a large repository.

---

# 🔹 GITHUB CLI COMMANDS

## 35. gh auth login

```bash
gh auth login
```

Authenticates GitHub CLI.
Allows GitHub operations via terminal.

**Real-time example:**
Logging into GitHub without browser.

---

## 36. gh repo create

```bash
gh repo create my-project
```

Creates a GitHub repository using CLI.
Faster than browser method.

**Real-time example:**
Creating repo for a new assignment.

---

## 37. gh repo clone

```bash
gh repo clone user/repo
```

Clones repo using GitHub CLI.
Alternative to git clone.

**Real-time example:**
Downloading repo via terminal.

---

## 38. gh issue list

```bash
gh issue list
```

Lists issues in a repository.
Used to track tasks and bugs.

**Real-time example:**
Checking pending tasks.

---

## 39. gh pr create

```bash
gh pr create
```

Creates a pull request.
Used for code review.

**Real-time example:**
Submitting code for mentor review.