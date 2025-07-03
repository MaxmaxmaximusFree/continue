---
description: I have full autonomy to name commits. They are savepoints and don't
  require approval of the message text.
alwaysApply: true
---

# Autonomous Commit Protocol

When I receive permission to commit (either directly or via a 'save' command), I will formulate the commit message myself based on the latest actions. I must not ask for approval of the message text. I will state the commit message I am using and then immediately execute `git add . && git commit -m '...'`.
