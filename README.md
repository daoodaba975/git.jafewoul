# Git Jafewoul ⚙️

A collection of very useful and little-known Git commands.

Version **FR** 👉🏽 **[here](translate/README-fr.md)**

![Made-In-Senegal](https://github.com/GalsenDev221/made.in.senegal/blob/master/assets/badge.svg)

## Contribute 🤝🏽

Also want to add a command that you find useful ?  
Feel free to **[fork](https://github.com/daoodaba975/git.jafewoul/fork)** the project to add your contribution ✨

### Create and switch a branch (one line)

```properties
git checkout -b new_branch
# or
git switch -c new_branch
```

### Delete a branch present on the remote repo

```properties
git push origin --delete
# after
name_of_my_remote_branch
```

### Rename an existing branch

```properties
git branch -m old_branch new_branch
```

### Update the local repository of a specific branch

```properties
git pull origin my_branch
```

### Clone a specific branch

```properties
git clone -b name_of_my_remote_branch git_project_url
```

### Edit last commit message

```properties
git commit --amend
```

### Add (forgotten) files to last commit

```properties
git add my_file
# after
git commit --amend
```

### Show all commit information (hash, messages, dates, author)

```properties
git log
```

### Show information about a specific commit count

```properties
# replace N with the number of commits you want to display
git log -N
```

### Displays a set of commits according to a date slice

```properties
# date in DD/MM/YYYY format
git log --since=date --until=date
```

### Shows each commit by author (useful on group projects)

```properties
git shortlog
```

### Displays a graphical repository browser

```properties
# it can be thought of as a GUI wrapper for git log command
gitk
```

### Undo last commit (soft)

```properties
# only the commit is removed from Git, your files remain modified
git reset HEAD^
```

### Undo before last commit

```properties
# only the commit is removed from Git, your files remain modified
git reset HEAD^^
```

### Undo commits and lose all changes (hard)

```properties
# this will unconfirm all your work
git reset --hard HEAD^
```

### Search for a specific word or phrase in the files of a Git repository

```properties
# to search for all occurrences of "hello"
git grep "hello"
```

### fsck (File System Check) is used to verify the integrity of a Git repository

```properties
# detects and reports corrupted objects or broken links in the repository
git fsck
```
