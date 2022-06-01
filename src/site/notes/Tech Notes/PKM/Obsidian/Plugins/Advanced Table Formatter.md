---
{"dg-publish":true,"dg-pass-frontmatter":true,"eleventyNavigation":{"key":"Advanced Table Formatter","parent":"Plugins"},"permalink":"/tech-notes/pkm/obsidian/plugins/advanced-table-formatter/","dgHomeLink":true,"dgPassFrontmatter":true}
---


# Advanced Table Formatter
This plugin enables hotkeys and enhanced editing of markdown tables including evaluating formulas.

Overview of the features:

-   Copy values from one cell, row, column, or range to another
-   Sum values from a column or range
-   Average (mean) values from a column or range
-   Value comparisons
-   Algebraic operations

## Formulas
Example formula:
`<!-- TBLFM: @>$2=sum(@I..@-1) -->`

The structure of this formula being:

`<!-- TBLFM: DESTINATION=SOURCE -->`

