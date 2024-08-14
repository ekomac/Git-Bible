# Git Command Bible with Examples

Here is a comprehensive list of essential Git commands, their definitions, and examples to help you master the basics and some advanced concepts:

## Basic Commands

1. **git init**: Initializes a new Git repository in the current directory.  
   *Example*:  
   ```bash
   git init my-repo
   ```
2. **git clone**: Creates a local copy of a remote repository.
   *Example*:
   ```bash
   git clone https://github.com/user/repo.git
   ```
3. **git add**: Stages changes in the working directory for the next commit.
   *Example*:
   ```bash
   git add file.txt
   ```
4. **git commit**: Records the staged changes as a new commit in the repository's history.
   *Example*:
   ```bash
   git commit -m "Initial commit"
   ```

5. **git status**: Shows the current state of the working directory and the staging area.
   Example:
   ```bash
   git status
   ```

6. **git log**: Displays the commit history of the repository.
   Example:
   ```bash
   git log
   ```

7. **git push**: Uploads local commits to a remote repository.
   Example:
   ```bash
   git push origin main
   ```

8. **git pull**: Downloads remote commits and merges them with the local repository.
   Example:
   ```bash
   git pull origin main
   ```

## Branching and Merging

9. **git branch**: Lists, creates, or deletes branches.
   Example:
   ```bash
   git branch new-feature
   ```

10. **git checkout**: Switches to a different branch or restores working tree files.
   Example:
   ```bash
   git checkout new-feature
   ```

11. **git checkout -b**: Creates a new branch and switches to it.
   Example:
   ```bash
   git checkout -b new-feature
   ```

12. **git merge**: Combines the histories of two branches.
   Example:
   ```bash
   git merge new-feature
   ```

13. **git rebase**: Replays commits from one branch onto another.
   Example:
   ```bash
   git rebase main
   ```

## Undoing Changes

14. **git reset**: Resets the current branch to a specified state, discarding or preserving changes.
   Example:
   ```bash
   git reset HEAD~1
   ```

15. **git revert**: Creates a new commit that undoes the changes made in a specified commit.
   Example:
   ```bash
   git revert abc1234
   ```

16. **git clean**: Removes untracked files from the working directory.
   Example:
   ```bash
   git clean -f
   ```

## Remote Repositories

17. **git remote**: Manages remote repositories.
   Example:
   ```bash
   git remote add origin https://github.com/user/repo.git
   ```

18. **git fetch**: Downloads objects and refs from a remote repository.
   Example:
   ```bash
   git fetch origin
   ```

19. **git push**: Uploads local commits to a remote repository.
   Example:
   ```bash
   git push origin main
   ```

20. **git pull**: Downloads remote commits and merges them with the local repository.
   Example:
   ```bash
   git pull origin main
   ```

## Stashing

21. **git stash**: Temporarily shelves changes in the working directory.
   Example:
   ```bash
   git stash
   ```

22. **git stash pop**: Restores the most recently stashed changes and removes the stash entry.
   Example:
   ```bash
   git stash pop
   ```

23. **git stash apply**: Restores the most recently stashed changes without removing the stash entry.
   Example:
   ```bash
   git stash apply
   ```

## Submodules

> A Git submodule is essentially a Git repository that exists as a subdirectory within another Git repository. This setup allows you to keep a separate repository (the submodule) linked to a main project repository. Submodules are particularly useful for managing dependencies or shared components across multiple projects.

24. **git submodule add**: Adds a new submodule to the repository.
   Example:
   ```bash
   git submodule add https://github.com/user/submodule.git
   ```

25. **git submodule update**: Updates the registered submodules to match the specified commit or branch.
   Example:
   ```bash
   git submodule update --init --recursive
   ```

26. **git submodule foreach**: Executes a command for each submodule.
   Example:
   ```bash
   git submodule foreach 'git pull origin main'
   ```

## Rewriting History

27. **git commit --amend**: Modifies the most recent commit.
   Example:
   ```bash
   git commit --amend -m "Updated commit message"
   ```

28. **git rebase -i**: Interactively rewrites the commit history.
   Example:
   ```bash
   git rebase -i HEAD~3
   ```

29. **git cherry-pick**: Applies the changes introduced by a specific commit to the current branch.
   Example:
   ```bash
   git cherry-pick abc1234
   ```

## Diff and Merge Tools

30. **git diff**: Shows changes between commits, the working tree, and the index.
   Example:
   ```bash
   git diff
   ```

31. **git mergetool**: Runs a merge conflict resolution tool to resolve conflicts.
   Example:
   ```bash
   git mergetool
   ```

32. **git difftool**: Runs a diff tool to show differences between files.
   Example:
   ```bash
   git difftool
   ```

## Tagging

33. **git tag**: Lists, creates, or deletes tags.
   Example:
   ```bash
   git tag v1.0
   ```

34. **git push --tags**: Uploads all local tags to the remote repository.
   Example:
   ```bash
   git push --tags
   ```

35. **git checkout <tagname>**: Switches to a specific tag.
   Example:
   ```bash
   git checkout v1.0
   ```

## Aliases

36. **git config --global alias.<alias-name> "<command>"**: Creates a shortcut for a Git command.
   Example:
   ```bash
   git config --global alias.co checkout
   ```

37. **git lg**: A custom alias for displaying a pretty commit lo.
   Example:
   ```bash
   git config --global alias.lg "log --oneline --graph --decorate"
   ```

38. **git status**: Shows the current state of the working directory and the staging area.
   Example:
   ```bash
   git status
   ```

39. **git status**: Shows the current state of the working irectory and the staging area.
   Example:
   ```bash
   git status
   ```

40. **git status**: Shows the current state of the working directory and the staging area.
   Example:
   ```bash
   git status
   ```
