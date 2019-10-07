# Lightshot Print Screen key Linux handler

This script handles global Print Screen key strokes for you to fully enjoy Lightshot on Linux.

It is a standard [POSIX](https://en.wikipedia.org/wiki/POSIX) shell script, it shall work on any Linux distribution.

## Pre-requisites

- Some necessary CLI tools:
	- [`xdotool`](http://manpages.ubuntu.com/manpages/bionic/man1/xdotool.1.html)
	- [`pgrep`](https://linux.die.net/man/1/pgrep)

- [X11 Window System](https://en.wikipedia.org/wiki/X_Window_System).

- [Lightshot](https://app.prntscr.com/en/wine-lightshot.html) properly installed into [Wine](https://www.winehq.org/).

## Usage instructions

### General

Just place it somewhere and put a path to it e.g. in Linux Mint 19 to the:

**Keyboard** → **Shortcuts** → **Custom Shortcuts** → click on button named **Add custom shortcut** and fill the form out.

### Command-line interface

Let me just point out, that there are many error checks along the whole script, so I advise you to run it within your terminal while your Lightshot is running to possibly debug any and all misbehaviors.

There is also the help switch

```
./lightshot-print-screen -h
```

which will point out the same possibility:

```
Script  : Lightshot Print Screen key Linux handler
Version : 2.0
GitHub  : https://git.io/fx2US
----------------------------------------------------------------------

Usage: lightshot_print_screen [-k "HotKey"]

   -k "HotKey": Optional switch requiring one argument,
		which is the print screen hotkey combination.

		For the left Control key and the Print Screen key:
		"Control_L+Print"
```

### Graphical interface

There is none.

## Screenshot from Linux Mint 19

![Screenshot from Linux Mint 19](https://i.imgur.com/JzvNnAo.png)

----------------------------------------

## Reporting bugs and suggestions

Please open a [new issue ticket](https://github.com/burianvlastimil/lightshot-print-screen-linux-handler/issues/new).
