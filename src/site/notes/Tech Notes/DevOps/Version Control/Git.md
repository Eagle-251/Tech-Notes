---
{"dg-publish":true,"permalink":"/tech-notes/dev-ops/version-control/git/","dgHomeLink":true,"dgPassFrontmatter":false}
---

## Github

### Template a release URL from Github API

```shell
wget $(curl -s https://api.github.com/repos/USERNAME/REPONAME/releases/latest | grep 'browser_' | cut -d\" -f4)
```
