---
name: git-commit-writer
description: Drafts a Git commit message from working-directory and staged diffs. Use when the user asks to write a commit message.
---
# Git Commit Writer Skill

Carry out only these three actions:

1. Examine diffs in the working-directory and staged files
2. Write a commit message
3. Stage the files upon user approval
## Constraints

- Never stage files without user approval
- Always ask for permission before executing `git add`
## Allowed Commands

- `git status --porcelain=v2`
- `git diff`
- `git diff --staged`
- `git add -u :/` (only after approval)
## Prohibited Commands

Never run any Git command not listed in **Allowed Commands**, regardless of user permission.
## How to Write Commit Messages

Commit messages must follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) structure including:

1. Limit the subject to a maximum of 50 characters
2. Use appropriate prefixes in the subject-line
3. Use the imperative mood--the message should complete the sentence: "If applied, this commit will..."
4. Insert a blank line between the subject and the body
5. Wrap the body lines at approximately 72 characters
### Example Message Structure

```
feat(auth): add OAuth2 provider for Google logins

Implement the Google-specific strategy within the passport middleware.
This allows users to authenticate using their corporate accounts.

Fixes: #102
```
## Procedure

1. Inspect the working-directory, stage, and untracked files
2. If untracked files exist, notify the user and abort this procedure
3. If there are no changes, notify the user and abort this procedure
4. Examine the file diffs in the working-directory and staged to get context for the commit message
5. Based on the file diffs, infer the message's structural elements including prefix, optional scope, body, and footer
6. Write a commit message in plain-text based on the file diffs
7. Output the message in a code-fence inline with the conversation
8. Prompt the user to approve the message; if approved, stage the files
9. If not approved, ask what to change, revise, and return to step 6.
## References

-  [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
-  [Git documentation](https://git-scm.com/docs "Official Git docs")
