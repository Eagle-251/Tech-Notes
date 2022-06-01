---
{"dg-publish":true,"permalink":"/tech-notes/linux/lshw/","dgHomeLink":true,"dgPassFrontmatter":false}
---

- ### `lshw`

  `lshw` is a cli tool to provide information on the current hardware configuration of your machine.
  For example, `sudo lshw -class network` will return information about configured NICs and network interfaces.
  The `-json` option can also be useful for accessing specific variables in scripts.