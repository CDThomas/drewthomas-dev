# Cheatsheet

Quick reference for features that I use frequently.

## Dealing with files and panes

* `:e filename`: open a new file to edit with name `filename` (need to use `:w` to actually save the new file)
* `:w` to write (save) - remapped to `<leader> s`
* `:q` to quit - remapped to `<leader> q`
* `:vsplit filename` (vertical split) or `:split filename` (horizontal split) to split panes with the specified file
* `<C-w-w>` to switch panes
* `:!rm filename` to delete a file (`:!` can run any shell command)

## Undo/Redo

* `u`: undo
* `U`: undo current line
* `<C-r>`: redo

## Misc

* `gu`: command to make text lowercase (ex: `guiw` to make current word lowercase)
* `gU`: command to make text uppercase (ex: `gUiw` to make current word uppercase)
  * Handy for things like env var names
