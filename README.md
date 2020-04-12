# python-stubs

## Description

A collection of Python type stubs I use in IntelliJ that aren't
available through normal channels. I maintain this junk by hand so
they may fall out of sync...


## Modules

### `gi` (pygobject-3.34.0):

Classes, methods and enumerations taken from PyGObject documentation
on an as-needed basis (Gtk and Gdk, mostly).

Source:
https://lazka.github.io/pgi-docs/#Gtk-3.0/classes/Window.html#Gtk.Window


## Usage

```bash
# IntelliJ + Python 3.7 (I'm sure there's a cleaner way)
ln -s $PWD/gi ~/.local/lib/python3.7/site-packages/gi-stubs

# TODO: add method that works with Sublime+Anaconda
```


