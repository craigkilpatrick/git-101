## Basic Git Commands
Taken from - http://guides.beanstalkapp.com/version-control/common-git-commands.html

### Make current directory a git repository
```
$ git init
```

### Add files to the staging area
```
$ git add <file or directory name>
```

### To add all files not staged:
```
$ git add .
```

### To stage a specific file:
```
$ git add index.html
```

### To stage an entire directory:
```
$ git add css
```

### Adding a commit with message
```
$ git commit -m "Commit message in quotes"
```

### Returns the current state of the repo
```
$ git status
```

### Show local branches
```
$ git branch
```

### Create new branch
```
$ git branch <branch_name>
```

### Delete a branch
```
$ git branch -d <branch_name>
```

### Checkout an existing branch
```
$ git checkout <branch_name>
```

### Checkout and create a new branch with that name
```
$ git checkout -b <new_branch>
```

### Merge changes into current branch
```
$ git merge <branch_name>
```

### Create a local working copy of an existing remote repo.
```
$ git clone <remote_url>
```

### Get latest version of a repo
```
$ git pull <branch_name> <remote_URL/remote_name>
```

### Send local commits to the remote repo
```
$ git push <remote_URL/remote_name> <branch>
```

### Save changes made when they're not in a state to commit
```
$ git stash
```

### Store current work with untracked files
```
$ git stash -u
```

### Show the chronological commit history for a repo
```
$ git log
```

### Show git log based on commit author
```
$ git log --<author>="Author Name"
```

### To remove a file from the working index (cached):
```
$ git rm --cached <file name>
```

### To delete a file (force):
```
$ git rm -f <file name>
```

### To remove an entire directory from the working index (cached):
```
$ git rm -r --cached <directory name>
```

### To delete an entire directory (force):
```
$ git rm -r -f <file name>
```