Tant
=======

Defines general aliases and functions for Tant.

Settings
--------

### Highlighting

If you have enabled color globally in *zpreztorc*, you may disable it for certain
commands.

To disable `ls` color, add the following line to *zpreztorc*; when coloring is
disabled, type indicators (\*, /, =>, @, =, |, %) will be appended to entries.

    zstyle ':prezto:module:tant:ls' color 'no'

To disable `diff` highlighting, add the following line to *zpreztorc*:

    zstyle ':prezto:module:tant:diff' color 'no'

To disable `make` highlighting, add the following line to *zpreztorc*:

    zstyle ':prezto:module:tant:make' color 'no'

Aliases
-------

### Disabled Spelling Correction

  - `ack`
  - `cd`
  - `cp`
  - `ebuild`
  - `gcc`
  - `gist`
  - `grep`
  - `heroku`
  - `ln`
  - `man`
  - `mkdir`
  - `mv`
  - `mysql`
  - `rm`

### Disabled File Globbing

  - `bower`
  - `fc`
  - `find`
  - `ftp`
  - `history`
  - `locate`
  - `rake`
  - `rsync`
  - `scp`
  - `sftp`

### General

  - `ln` links files and directories interactively.
  - `mkdir` creates directories, including intermediary directories.
  - `type` displays all the attribute values of a shell parameter.

Functions
---------

### General

  - `slit` prints columns *1, 2, 3 ... n*.

### Files and Directories

  - `mkcd` makes a directory and changes to it.
  - `pdfsearch` search throug pdfs

### VIM

  - `addword` Adds a word to the dictionary file

### Developer

  - `diff` highlights diff output (requires `colordiff` or `Git`).
  - `make` highlights make output (requires `colormake`).

### Resource usage

  - `psu` displays user owned processes status.

Authors
-------

*The authors of this module should be contacted via the [issue tracker][1].*

  - [Robby Russell](https://github.com/robbyrussell)
  - [Suraj N. Kurapati](https://github.com/sunaku)
  - [Sorin Ionescu](https://github.com/sorin-ionescu)

[1]: https://github.com/sorin-ionescu/prezto/issues
