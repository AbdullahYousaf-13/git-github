# Git/Github

A repo covering basic concepts of Git and Github

## CMD Commands

- 
- Going back one folder: `cd ..`
- Going to desired folder in the current directory: `cd home => cd [my-dir]` (Use tab to get full name of directory)
- To list the contents of current folder: `ls` or `dir`
- To create new directory: `mkdir [my-dir]` (name of the directory)
- To delete a directory: rmdir [my-dir] (name of the directory)

- To create new file: `touch [my-dir]` (name of the file)
- To delete a file: rm `[my-dir]` (name of the file)

- To open a new file with the Text editor: `[text-editor]` (name of the editor) `[my-dir]` (name of the file)


## Git Commands

- To set the author globally for all repos in machine, configure user name and user email:

  `git config --global [user.name]`

  `git config --global [user.email]`

- To set the author for current repo, configure user name and user email:

  `git config [user.name]`

  `git config [user.email]`

- To check who is making changes: `git config user.name`

- Checking the status of a file:
  `git status`
- Intializing git repo: `git init` (used so git can track any changes made)

- Adding a file to staging area: `git add [my-dir]` (name of the file)

- Removing a file from staging area: `git reset [my-dir]` (name of the file) or`git rm --cached [my-dir]` (name of the file)

- Adding all files in staging area at once: `git add .`

- Making commit: `git commit -m "added [my-dir] and
[my-dir-2]"`(any message explaning work done in commit)

- To see commit history: `git log`

- To see commit history in short: `git log --oneline`

- Checkout commit:`` (shows code at desired point in time, does not change commit history)

- Revert commit:``

- Reset commit:``
