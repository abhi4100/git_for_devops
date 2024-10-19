echo "# Git Commands Summary

This document outlines the Git commands executed in the repository setup and management process.

## Initial Setup

1. **Initialize a new Git repository**
   \`\`\`bash
   git init
   \`\`\`

2. **Create files**
   \`\`\`bash
   touch file file2
   \`\`\`

3. **Stage all changes for commit**
   \`\`\`bash
   git add .
   \`\`\`

4. **Commit changes with a message**
   \`\`\`bash
   git commit -m \"testing\"
   \`\`\`

5. **Check the status of the repository**
   \`\`\`bash
   git status
   \`\`\`

6. **Configure Git user information**
   \`\`\`bash
   git config --global user.name \"abhi4100\"
   git config --global user.email \"abhisheksingh441997@gmail.com\"
   \`\`\`

7. **Make another commit**
   \`\`\`bash
   git commit -m \"testing\"
   \`\`\`

8. **View commit history**
   \`\`\`bash
   git log
   \`\`\`

## File Management

9. **Create another file**
   \`\`\`bash
   touch file3
   \`\`\`

10. **Stage changes again**
    \`\`\`bash
    git add .
    \`\`\`

11. **Commit the changes**
    \`\`\`bash
    git commit -m \"hsafh\"
    \`\`\`

## Push Changes

12. **Force push changes to the remote repository**
    \`\`\`bash
    git push -f origin main
    \`\`\`

## Branch Management

13. **Create and switch to a new branch**
    \`\`\`bash
    git checkout -b dev
    \`\`\`

14. **Check the status of the new branch**
    \`\`\`bash
    git status
    \`\`\`

15. **Create another file**
    \`\`\`bash
    touch file5
    \`\`\`

16. **Stage and check status again**
    \`\`\`bash
    git add .
    git status
    \`\`\`

17. **Switch back to the master branch**
    \`\`\`bash
    git checkout master
    \`\`\`

18. **Check the status on the master branch**
    \`\`\`bash
    git status
    \`\`\`

19. **View commit history in a condensed format**
    \`\`\`bash
    git log --oneline
    \`\`\`

20. **Switch back to the dev branch**
    \`\`\`bash
    git switch dev
    \`\`\`

21. **Check the status on the dev branch**
    \`\`\`bash
    git status
    \`\`\`

## Summary
This summary provides an overview of essential Git commands for initializing a repository, managing files, committing changes, and handling branches." > commands.md
