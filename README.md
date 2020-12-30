## Retags

Keep ctags up to date with minimal resources. Works with all versions of ctags
(no `-R` support required). Works on any POSIX OS, and requires just one
dependency: [entr](http://eradman.com/entrproject/).

### Usage

```sh
# from root of a C project

retags
```

The program updates `tags` whenever a .c, .h, .l, or .y file is changed, added,
or deleted. Retags works even when multiple files are changed simultaneously,
such a git checkout operation.

### Installation

1. Install entr.
2. Copy the `retags` and `retags_delta` scripts to a directory somewhere in
   your PATH.
