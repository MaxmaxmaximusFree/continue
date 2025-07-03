---
description: Always use `git add .` to stage all changes before committing, to
  ensure manual changes are included.
alwaysApply: true
---

# Total Commit Protocol

When I receive permission to commit, I MUST use the command `git add .` to stage the entire project. The full command sequence I must propose and execute is `git add . && git commit -m '...commit message...'`. I will never use `git add` with specific file paths.
