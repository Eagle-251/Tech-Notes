---
{"dg-publish":true,"permalink":"/tech-notes/linux/lspci/","dgHomeLink":true,"dgPassFrontmatter":false}
---

- ### `lspci`

  Very similar in output to `lsub`except this command is concerned with PCI devices

  Example:

  - `lspci -kvm` will give return all pci devices in a readable form with the drivers being used for each device included.