# st 

This is a clone of a clone of [suckless.org](http://suckless.org)'s st, based off
the work of GitHub user l3pp4rd.


## Requirements

- Xlib header files - location of these might differ, edit config.mk
- xft lib headers.
- Inconsolata.ttf fonts, unless you change it in config.h

## Installation

Edit config.mk to match your local setup (**st** is installed into the
**/usr/local** namespace by default).

**NOTE:** to have unicode character support, install **freetype2** library
headers.

**NOTE:** **ranger** file manager may not preview images well, when having
transparency enabled.

## Transparency

You need to run **compton** or **xcompmgr** in order to have transparent
terminal.

### Ubuntu required libraries

    apt-get install libx11-dev libxext-dev libxft-dev fonts-inconsolata

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


nooooo
