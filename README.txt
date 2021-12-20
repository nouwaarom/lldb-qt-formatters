# Qt formatters for lldb
This project is a copy from the debugging bridges that are delivered with qt creator.
I copied pygdbmi for convenience so that the only thing that is required to get this working is to copy this repo.

To use the lldb bridge, clone this repo.
Then add the following to you `.lldbinit` file:
```
command script import <location_of_this_repo>/lldbbridge.py
```
Make sure that loading `.lldbinit` files is enabled.
