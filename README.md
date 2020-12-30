## Retags

Keep ctags up to date. Works with all versions of ctags (no `-R` support
required). Works on any POSIX OS, and requires just one dependency:
[entr](http://eradman.com/entrproject/).

### Usage

```sh
# from root of a C project

retags
```

The script updates `tags` whenever a .c, .h, .l, or .y file is changed, added,
or deleted.

### Installation

1. Install entr.
2. Copy the `retags` script to a directory somewhere in your PATH.
