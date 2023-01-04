## Resolve conflict issues

### Step 1
```azure
git pull --rebase origin <branch_name>
```

### Step 2
Change conflicted files manually or use commands.
```azure
git checkout --theirs -- .
```
or,
```azure
git checkout --ours -- .
```

### Step 3
```azure
git rebase --skip
```

### Step 4
```azure
git add conflicted_files
```

### Step 5
```azure
git push origin <branch_name>
```

-------------------------
source: https://www.simplilearn.com/tutorials/git-tutorial/merge-conflicts-in-git
-------------------------