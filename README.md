# [sublime-velma](https://github.com/jthuraisamy/sublime-velma)

![Preview](http://i.imgur.com/H7CKHRW.png)

## Features

* Syntax Highlighting
* Build System (Outputs Trace and Registers)
* Comment with <kbd>Ctrl</kbd> + <kbd>/</kbd>

## Installation

Go to `Preferences -> Browse Packages`, and then either download and unzip this package into that directory, or:

``` bash
git clone https://github.com/jthuraisamy/sublime-velma-syntax.git "sublime-velma-syntax"
```

## Activation

### Syntax Highlighting

If the file has a `.velma` extention, syntax highlighting should already be enabled if this package is installed. If not, try one of the following methods:

* Select VELMA from the list of supported languages in the bottom right corner of the status bar
* <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> and search for "VELMA"

### Build System

If the Build System is set to Automatic and the current code is recognized as VELMA code, then it should be enabled with <kbd>Ctrl</kbd> + <kbd>B</kbd>. If not, select `Tools -> Build System -> VELMA`.

N.B.:
* The binaries for VELMA must be in your system's PATH.
* This has not been tested on Linux or OS X, just Windows.

## Licence

[MIT](http://www.tldrlegal.com/l/MIT)