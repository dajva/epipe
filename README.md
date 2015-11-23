epipe
=====

epipe redirects stdin to emacs. Use it on command line like so:
```
$ echo "foo" | epipe
```

Installation
------------
Download and point your PATH at the location of epipe:
```
$ export PATH=/path/to/epipe-dir:$PATH
```

Usage
-----
```
epipe redirects stdin to an emacs buffer
Example: 'echo "foo" | epipe'

    -v	Verbose mode also output to stdout.
    -h	Shows this message.
``` 
