# Git Basics

## Check repository status
```bash
git status
```

## Stage a file or all changes
```bash
git add README.md
git add .
```

## Commit staged changes
```bash
git commit -m "Add a useful message"
```

## Review commit history
```bash
git log --oneline
```

## Unstage a file
```bash
git restore --staged <file>
```

## Discard changes in a tracked file
```bash
git restore <file>
```

Be careful: `git restore <file>` discards uncommitted changes to that file.
Practice note: Review the Git add, commit, and status commands.
