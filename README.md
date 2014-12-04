Docker Scripts
==============

Very small script(s) that may or may not be useful while working with Docker.
Created for my personal use but feel free to copy or use in any way.

**Install**: Make sure the scripts in `bin/` in your path, rename if preferred.

dr-nsenter
----------

Runs the [nsenter](https://github.com/jpetazzo/nsenter) command for the
specified container.

Requires nsenter to already be installed:

    docker run -v /usr/local/bin:/target jpetazzo/nsenter
