# Lightshot Print Screen key Linux handler

This script handles global Print Screen key strokes for you to fully enjoy Lightshot on Linux.

It is a standard [POSIX](https://en.wikipedia.org/wiki/POSIX) shell script, it should work in any [Linux](https://en.wikipedia.org/wiki/Linux) distribution (more precisely, your [shell](https://en.wikipedia.org/wiki/Unix_shell)).

----------------------------------------

## Pre-requisites

- One necessary CLI tool to have manually installed:
	- [`xdotool`](http://manpages.ubuntu.com/manpages/bionic/man1/xdotool.1.html): In Ubuntu the package is in the _universe_ part of official archive.

- [X11 Window System](https://en.wikipedia.org/wiki/X_Window_System).

- [Lightshot](https://app.prntscr.com/en/wine-lightshot.html) properly installed into [Wine](https://www.winehq.org/).

----------------------------------------

## Usage instructions

### Download and Preparation

Visit the [latest release download page](https://github.com/burianvlastimil/lightshot-print-screen-linux-handler/releases/latest). If you directly download the file ```lightshot_print_screen```, you will need to open your terminal and give it **permission to read and execute** to all users with:
```lang-sh
chmod 755 lightshot_print_screen
```

### General

Place it somewhere and put a path to it e.g. in Linux Mint 19 to the:

**Keyboard** → **Shortcuts** → **Custom Shortcuts** → click on button named **Add custom shortcut** and fill the form out.

### Command-line interface

Let me just point out, that there are many error checks along the whole script, so I advise you to run it within your terminal while your Lightshot is running to possibly debug any and all misbehaviors.

There is also the help switch:

```
./lightshot-print-screen -h
```

which will point out the possibility for you to feed the key combination you have configured in your Lightshot interface without ever editing the script:

```
Script  : Lightshot Print Screen key Linux handler
Version : 2.2
GitHub  : https://git.io/fx2US
----------------------------------------------------------------------
Usage: lightshot_print_screen [-k "HotKey"]

-k "HotKey": Optional switch requiring one argument,
             which is the print screen hotkey combination.
             For the left Control key and the Print Screen key:
             "Control_L+Print" for example.
```

### Graphical interface

There is none.

----------------------------------------

## Screenshot from Linux Mint 19.3

![Screenshot from Linux Mint 19.3](https://i.imgur.com/AyhK0uu.png)

----------------------------------------

## Reporting bugs and suggestions

Please open a [new issue ticket](https://github.com/burianvlastimil/lightshot-print-screen-linux-handler/issues/new).
