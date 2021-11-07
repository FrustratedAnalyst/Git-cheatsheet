# **Git**
Git is the most commonly used **version control system.** Git tracks the changes you make to files, so you have a record of what has been done, and you can revert to specific versions should you ever need to. Git also makes collaboration easier, allowing changes by multiple people to all be merged into one source.

## Content:
1. **git init**
2. **git clone**
3. **git status**
4. **git add**
5. **git commit**
6. **git diff**
7. **git log**
8. **git tag**
9. **git branch**
10. **git checkout**
11. **git merge**
12. **git rebase**


### **1. git init**:
git init is one way to start a new project with Git.

### syntax

```git init ```


### **2. git clone**:
git clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository.

### syntax

```git clone target_repo_link```

We can rename a repository while cloneing it.

### syntax

```git clone target_repo_link chosen_name```


### **3. git clone**:
The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git

### syntax

```git status```

### **4. git add**:
The git add command adds a file to the Git staging area. This area contains a list of all the files you have recently changed. Your repository will be updated the next time you create a commit with your changes. Therefore, running the git add command does not change any of your work in the Git repository.

### syntax

```git add file_name```

### **5. git commit**:
The git commit command captures a snapshot of the project's currently staged changes. Committed snapshots can be thought of as “safe” versions of a project—Git will never change them unless you explicitly ask it to. These two commands git commit and git add are two of the most frequently used.

### syntax

```git commit```

We can add a  message to every commit to make them more informative, we can do this using ```-m``` flag

### syntax
```git commit -m "message"```

### **6. git diff**:
git diff is a multi-use Git command that when executed runs a diff function on Git data sources. These data sources can be commits, branches, files and more. ... The git diff command is often used along with git status and git log to analyze the current state of a Git repo.

### syntax

```git diff```

To show the changes between the index and the HEAD (which is the last commit on this branch). This shows what has been added to the index and staged for a commit.

```git diff --cached```

### **7. git log**:
Git log is a utility tool to review and read a history of everything that happens to a repository. Multiple options can be used with a git log to make history more specific. Generally, the git log is a record of commits.

### syntax

```git log```


By default, the git log statement returns a full log entry for each commit made to a repository. You can retrieve a list of commit IDs and their associated commit messages using the –oneline flag. We can see the commit IDs and the first line of the messages associated with a commit.

```git log --oneline```

The --decorate flag makes git log display all of the references (e.g., branches, tags, etc) that point to each commit. This lets you know that the top commit is also checked out (denoted by HEAD ) and that it is also the tip of the main branch.

```git log --decorate```

### **8. git tag**:
Tags are ref's that point to specific points in Git history. Tagging is generally used to capture a point in history that is used for a marked version release (i.e. v1. 0.1). A tag is like a branch that doesn't change. Unlike branches, tags, after being created, have no further history of commits.

### syntax

```git tag tag_name```

### **9. git branch**:
Git branches are effectively a pointer to a snapshot of your changes. Instead of copying files from directory to directory, Git stores a branch as a reference to a commit. In this sense, a branch represents the tip of a series of commits—it's not a container for commits.

### syntax

```git branch branch_name```

### **10. git checkout**:
The git checkout command is used to switch between branches in a repository. It checks the branches and updates the files in the working directory to match the version already available in that branch, and it forwards the updates to Git to save all new commit in that branch.

### syntax

```git checkout branch_name```

### **11. git merge**:
Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch. The current branch will be updated to reflect the merge, but the target branch will be completely unaffected.

### syntax

```git merge branch_name```

### **12. git rebase**:
A rebase is what you do when you combine a commit or series of commits to a new commit. It is similar to merging in that it moves changes from one branch to another. Rebasing allows you to rewrite the history of a Git repository. When you run a rebase operation, it merges the entire history of two branches into one.

### syntax

```git rebase branch_name```

## Bonus
```git rm --cached```
The Git rm –cached flag removes a file from the staging area. The files from the working directory will remain intact. This means that you'll still have a copy of the file locally. The file will be removed from the index tracking your Git project.



















