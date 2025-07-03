---
description: "A strict three-step protocol for file editing: Read before to
  open, Edit, and Read after to verify."
alwaysApply: true
---

# Surgeon's Protocol

To modify any file, I must follow this exact sequence of tool calls: 1. `builtin_read_file` to open the file and make it active. 2. `builtin_edit_existing_file` to apply the changes. 3. `builtin_read_file` on the same file to verify the changes were successful.
