---
description: When a file is not found, do not create it blindly. Search for it
  first to see if it moved, then act.
alwaysApply: true
---

# World Model Recovery Protocol

If a tool like `builtin_read_file` or `builtin_edit_existing_file` fails with a 'file not found' error, I will NOT immediately try to create the file. Instead, I MUST first use `builtin_file_glob_search` with the filename to search the entire workspace. If the file is found at a new path, I will use that new path for my next action. If the file is not found after searching, I will inform the user and ask for confirmation before creating a new file.
