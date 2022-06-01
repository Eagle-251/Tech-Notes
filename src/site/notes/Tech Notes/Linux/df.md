---
{"dg-publish":true,"dg-pass-frontmatter":true,"eleventyNavigation":{"key":"df","parent":"Linux"},"permalink":"/tech-notes/linux/df/","dgHomeLink":true,"dgPassFrontmatter":true}
---


## `df`
This command gives information about filesystems in use by the system.

Examples:
  - `df -h` returns filesystems with their usage in a human readable format
  - `df -h path/to/file` the same as above but will return the filesystem containing the path specified
  - `df -x tmpfs` exclude temporary filesystems from the output