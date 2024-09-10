
## Pull Requests

- **Why use PRs?**
    - Code review and feedback before merging.
    - Required for contributing to repositories you don't have direct access to.
- **Forking**: Create your own copy of a repository for making changes, and then open a PR to suggest these changes for integration.

```mermaid
graph TD;
    A[Original Repo] --> B[Fork];
    B --> C[Local Clone];
    C --> D[Create Feature Branch];
    D --> E[Make Changes];
    E --> F[Push Changes to Fork];
    F --> G[Open PR in Original Repo];

```

## Merge Conflicts

- **When do conflicts occur?**
    - Conflicting changes in the same line of code in different branches.
- **Steps to Resolve**:
    1. Identify the conflict (Git shows it clearly).
    2. Choose the correct changes by editing the file manually or using a merge tool.
    3. Commit the resolved changes.