# TapTux Package Index

This file is packguin's package index (see the `packguin source` command).

Format: each category is a "## Heading" line, followed somewhere below it
by one fenced code block tagged "packguin" (three backticks, then the word
packguin, on their own line). Inside that block, one package per line, with
5 fields separated by "|":

    name | size | link | description | author

Rules:
- "link" must be a raw file URL (raw.githubusercontent.com), not a normal github.com page link.
- "name" must match the class the file defines (e.g. quill -> QuillCommand).
- Package names must be unique across the whole file, not just per category.
- Every fenced code block must be closed (three backticks on their own line at the end).

## Editors

```packguin
# name | size | link | description | author
quill | 4 KB | https://raw.githubusercontent.com/DevoraInc/TapTux/TapTux/packages/quill.py | A small nano-like full-screen text editor | DevoraInc
