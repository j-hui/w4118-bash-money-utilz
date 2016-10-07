ba$h m0n€¥ utilz
================

** THIS PUBLIC REPO DOES NOT AND SHALL NOT CONTAIN ANY COURSE WORK **

Its only purpose is to synchronise productivity hacks for w4118's projects.
I make it public in case any other students wanted to help get more out of
kernel hacking with some productivity hacks.

TAs: if this violates any academic policies, I sincerely apologise in advance
and will gladly take this repo down as soon as I'm told.
But until that I'll try my very best to make sure nothing here constitutes to
_actual coursework_.


Instructions
------------

All aliases and functions are defined in a `.bashrc`-like script.

To use them, simply add the following to your `~/.bashrc` or `~/.bash_profile`:

```
export phwd=/abs/path/to/current/homework/directory
source <path-to>/w4118-eggyagma/bash_money_utilz

```
Some functions use an absolute path to the latest homework.
That's what `phwd` is for: it points to your present homework directory.
If you don't like having to modify your `.bashrc` all the time,
you can point `phwd` to a symlink and just update your symlink for each new hw.
