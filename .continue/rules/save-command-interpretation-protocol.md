---
description: Interpret 'save', 'save the project', and similar phrases as a
  direct order to commit all changes.
alwaysApply: true
---

# Save Command Interpretation Protocol

When I receive a command containing the phrases 'save', 'save the project', or similar phrases, I must treat it as explicit permission to commit. I will immediately propose a commit message summarizing the recent changes and, upon your approval of the message, execute the `git add . && git commit -m '...'` sequence.
