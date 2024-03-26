# Git Bash Commands

This document provides a list of commonly used Git Bash commands.

## File and Directory Manipulation

- `ls`: Lists all files and directories in the current directory.
- `cd <directory>`: Changes the current directory to the specified directory.
- `pwd`: Prints the path of the current directory.
- `touch <file>`: Creates a new file.
- `mkdir <directory>`: Creates a new directory.
- `rm <file>`: Deletes a file.
- `rmdir <directory>`: Deletes a directory (only if it's empty).
- `cp <source> <destination>`: Copies a file or directory from source to destination.
- `mv <source> <destination>`: Moves a file or directory from source to destination.
- `cat <file>`: Displays the content of a file.
- `nano <file>` or `vi <file>`: Opens a file in the nano or vi text editor.
- `find . -name <filename>`: Finds a file in the current directory and its subdirectories.
- `grep <pattern> <file>`: Searches for a pattern in a file.
- `code <filename>`: Opens the file

## System Operations

- `echo <text>`: Prints the specified text to the console.
- `history`: Shows the command history.
- `clear`: Clears the console screen.
- `exit`: Closes the Git Bash terminal.
- `man <command>`: Displays the manual page for the specified command.
- `less <file>`: Views the content of a file one page at a time.
- `head <file>`: Displays the first 10 lines of a file.
- `tail <file>`: Displays the last 10 lines of a file.
- `chmod <permissions> <file>`: Changes the permissions of a file.
- `chown <user> <file>`: Changes the owner of a file.
- `date`: Displays the current date and time.
- `cal`: Displays a calendar of the current month.
- `df`: Displays disk usage.
- `du <directory>`: Displays the disk usage of the specified directory.
- `ps`: Displays the currently active processes.
- `top`: Displays a real-time overview of currently running system processes.
- `kill <pid>`: Terminates the process with the specified process ID (pid).

Remember to replace `<directory>`, `<file>`, `<source>`, `<destination>`, `<filename>`, `<pattern>`, `<text>`, `<command>`, `<permissions>`, `<user>`, and `<pid>` with your specific details.




# Git Commands

## Repository Setup

- `git init`: Initializes a new Git repository.
- `git clone <repository>`: Creates a copy of a remote repository on your local machine.

## Basic Snapshotting

- `git add <file>`: Adds a file to the staging area in preparation for a commit.
- `git commit -m "<message>"`: Commits the staged changes and prepares them to be pushed to a remote repository.

## Branching and Merging

- `git branch`: Lists all local branches in the current repository.
- `git branch <branch>`: Creates a new branch.
- `git checkout <branch>`: Switches to the specified branch and updates the working directory.
- `git merge <branch>`: Merges the specified branch’s history into the current branch.

## Sharing and Updating

- `git push <remote> <branch>`: Pushes committed changes to a remote repository.
- `git pull <remote> <branch>`: Fetches changes from a remote repository and merges them into the current branch.

## Inspection and Comparison

- `git status`: Shows the status of changes in the current repository.
- `git log`: Shows all commits, starting with the latest.
- `git diff`: Shows the file differences not yet staged.
- `git diff --staged`: Shows file differences between staging and the last file version.

## Undoing Changes

- `git reset <file>`: Unstages the file, but preserve its contents.
- `git checkout -- <file>`: Discards changes to the file.
- `git revert <commit>`: Creates a new commit that undoes all of the changes made in `<commit>`, then apply it to the current branch.
- `git reset --hard <commit>`: Discards all history and changes back to the specified commit.

Remember to replace `<repository>`, `<file>`, `<message>`, `<remote>`, `<branch>`, and `<commit>` with your specific details.




# Additional Git Commands


## Stashing and Cleaning

- `git stash`: Temporarily saves changes that you don't want to commit immediately. You can apply the changes later with `git stash pop`.
- `git clean -n`: Shows which files would be removed from working directory. Use the `-f` option in place of `-n` to actually remove the files.

## Tagging

- `git tag`: Lists all tags in the repository.
- `git tag <tag>`: Creates a lightweight tag.
- `git tag -a <tag> -m "<message>"`: Creates an annotated tag with a message.

## Remote Repositories

- `git remote`: Lists remote repositories.
- `git remote add <name> <url>`: Adds a remote repository.
- `git remote rm <name>`: Removes a remote repository.

## Advanced Git

- `git rebase <branch>`: Reapply commits on top of another base tip.
- `git bisect`: Use binary search to find the commit that introduced a bug.

## Git Configuration

- `git config --list`: Lists all Git configuration settings.
- `git config --global user.name "<name>"`: Sets a name that is identifiable for credit when review version history.
- `git config --global user.email "<email address>"`: Sets an email address that will be associated with each history marker.

Remember to replace `<tag>`, `<message>`, `<name>`, `<url>`, `<branch>`, and `<email address>` with your specific details.