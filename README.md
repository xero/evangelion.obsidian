# evangelion obsidian

## css snippets

- [ascii.css](https://github.com/xero/evangelion.obsidian/blob/snippets/ascii.css) - code block fixes for text art
- [topaz.css](https://github.com/xero/evangelion.obsidian/blob/snippets/topaz.css) embedds the classic amiga ascii art font "topaz" into code blocks
- [hide-meta.css](https://github.com/xero/evangelion.obsidian/blob/snippets/hide-meta.css) - hides front matter in reading and live preview modes
- [midnight.css](https://github.com/xero/evangelion.obsidian/blob/snippets/midnight.css) - black background for a note
- [hide-tbl.css](https://github.com/xero/evangelion.obsidian/blob/snippets/hide-tbl.css) - headers only tables with zero margin (reading view only)

### installing

add these to your `/.obsidian/snippets` folder then enable them in **settings > appearance**

### using

add a front matter property called _"cssclasses"_ and use the name of the snip you want to apply. each work on a per-note basis.

#### front matter example
```
---
id: rad text-art
tags:
  - ascii
  - art
cssclasses:
  - ascii
  - topaz
  - midnight
  - hide-meta
---
```

# license

![kopimi logo](https://gist.githubusercontent.com/xero/cbcd5c38b695004c848b73e5c1c0c779/raw/6b32899b0af238b17383d7a878a69a076139e72d/kopimi-sm.png)

all files and scripts in this repo are released [CC0](https://creativecommons.org/publicdomain/zero/1.0/) / [kopimi](https://kopimi.com)! in the spirit of _freedom of information_, i encourage you to fork, modify, change, share, or do whatever you like with this project! `^c^v`
