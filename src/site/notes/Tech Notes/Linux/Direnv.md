---
{"dg-publish":true,"dg-pass-frontmatter":true,"eleventyNavigation":{"key":"Direnv","parent":"Linux"},"permalink":"/tech-notes/linux/direnv/","dgHomeLink":true,"dgPassFrontmatter":true}
---

# Direnv

A tool to create directory specific .env files. Each will get loaded by the shell when entereing the directory.

## Snippets

### Shell Integration

```fish
direnv hook fish | source
```

### Add env variable

echo "export WHATEVER=variable" > .envrc
direnv allow

