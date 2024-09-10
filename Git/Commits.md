Crafting the Perfect Commit:
- Select the right changes: Only include changes from a single topic in a commit.
- Avoid large commits: Separate different topics into distinct commits. 
- Use the Git staging area: Allows selective staging of files or even parts of files for more precise commits.
```
git add <file-name>        # Add specific file
git add -p <file-name>     # Add specific parts of the file
```

### Perfect Commit Message Structure

1. **Subject line**: Brief summary (≤ 80 characters).
2. **Body**:
    - What's different?
    - Why was the change made?
    - Any warnings or notes?
