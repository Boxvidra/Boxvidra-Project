# TapTux Package Index

This file is packguin's package index (see `packguin source`). Each
category is a "## Heading" immediately followed by one ```packguin code
block. Inside the block, one package per line, 5 "|"-separated fields:

    name | size | link | description | author

- "link" must be the **raw** URL of the package's .py file (raw.githubusercontent.com, not a normal github.com blob link).
- "name" must match the class the file defines (e.g. `quill` -> `QuillCommand`), since that's what CommandLoader enforces.
- Package names must be unique across the whole file, not just per category.

## Editors

```packguin
# name | size | link | description | author
quill | 4 KB | https://raw.githubusercontent.com/DevoraInc/TapTux/TapTux/packages/quill.py | A small nano-like full-screen text editor | DevoraInc
