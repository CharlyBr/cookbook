# Vim

start with running `vimtutor`

## Deleting text

* `dd` delete current line
* `d^` detele from current position to the beginning of line
* `d$` detele from current position to the end of line
* `dG` delete from current line to the end of file
* `diw` delete the current word
* `dw` delete from current position to the end of the word
* `di(` delete everything within the current parenthesis.
* `di"` delete everything between the current quotes.

## Execute commands

open term and execute a command

```
:! [command]
```

paste command output in current file

```
:.! [command]
```
