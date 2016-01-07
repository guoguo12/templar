Templar
=======

This repository contains **Templar v1.3.2**. For the latest version, see [albert12132/templar](https://github.com/albert12132/templar).

If you're getting an error like

```
# python3 generate.py hw0
usage: templar [-h] [-s SOURCE] [-t TEMPLATE] [-d DESTINATION] [-c CONFIG]
               [--print] [--debug] [--version]
templar: error: unrecognized arguments: compile hw.html -m
```

you might have Templar 2 installed when really what you need is Templar 1. (Check your Templar version with `templar --version`. If it doesn't work, you're on Templar 1.)

## Installation

If you have Templar 2 already installed, uninstall it. Something like `pip3 uninstall templar` should do the trick. If not, try finding and manually removing the files/directories below:

```
/usr/local/bin/templar
/usr/local/lib/python3.4/dist-packages/templar-2.0.1.egg-info
/usr/local/lib/python3.4/dist-packages/templar/
```

Now clone this repo, `cd` into it, and run `python3 setup.py install`.
