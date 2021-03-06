filter
======

Filter stdin using `grep`.


Installation
------------

I recommend installing `filter` in the `/usr/local/bin` directory using the
following command:

    cp filter /usr/local/bin


Usage
-----

`filter` is really just a wrapper around `grep` with the flags:
- `h`: Suppress the prefixing of filenames on output.
- `v`: Invert the sense of matching, to select non-matching lines.

It is used just like you would use `grep`. You can also include other `grep`
flags, which will override the built-in `grep` flags of `filter`, such as:
- `H`: Print the filename for each match.


Dependencies
------------
- grep


License
-------

Copyright (C) 2021 Robert Coffey

This is free software: you can redistribute it and/or modify it under the terms
of the GNU General Public License version 3.
