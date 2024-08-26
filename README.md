## Common Git Commands

Check status of the repo:
```
git status
```

View differences between your working copy and current "HEAD" in git:
```
git diff
```

Creating a new branch:
```
git branch <branch-name>
```

Viewing branches:
```
git branch or git branch --list
```

Deleting a branch:
```
git branch -d <branch-name>
```

First you should switch to the dev branch:
```
git checkout dev
```

Before merging, you should update your local dev branch:
```
git fetch
```

Finally, you can merge your feature branch into dev:
```
git merge <branch-name>
```

Add remote repository
```
git remote <command> <remote_name> <remote_URL>
```

List named remote repositories
```
git remote -v
```