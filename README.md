# dmenu - dynamic menu

dmenu is an efficient dynamic menu for X.

This is my _patched_ fork of dmenu, from [suckless](https://tools.suckless.org/dmenu/)

## Requirements

In order to build dmenu you need the Xlib header files.

## Patching

Patches have already been applied in the source, and are left in the
`patches` directory both for reference and incase they need to be
reapplied in future to match up with any dmenu updates.

## Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install

## Running dmenu

See the man page for details.
