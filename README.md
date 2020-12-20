## Retags

Keep ctags up to date with minimal resources. Works with all versions of ctags
(no `-R` support required). Works on any POSIX OS, and requires just one
dependency: [entr](http://eradman.com/entrproject/).

### Usage

```sh
# from root of a C project

retags
```

The program updates `tags` whenever a .c, .h, .l, or .y file is changed or
added. Single file updates are fast, requiring few system resources.

If a source file is deleted, or more than one file is changed simultaneously,
you'll need to regenerate the tags file. Either restart the retags program, or
send it a SIGUSR1 signal to do this.

### Installation

1. Install entr.
2. Copy the `retags` and `retags_delta` scripts to a directory somewhere in
   your PATH.
