---
{"dg-publish":true,"eleventyNavigation":{"key":"Fish","parent":"Shells"},"permalink":"/tech-notes/shells/fish/","dgHomeLink":true,"dgPassFrontmatter":true}
---

# Fish
### Common Tasks

**Add To Path**

Call the inbuilt function `fish_add_path`, use `-a` to append to the existing path:
- `fish_add_path -a $HOME/.local/bin`

**Create an Alias**
Similar syntax to [[Tech Notes/Shells/Bash|Bash]]:
- `alias ls "ls -al"`
Unlike [[Tech Notes/Shells/Bash|Bash]], fish takes care of persistence of the alias through the `funcsave` function:
- `funcsave ls`

