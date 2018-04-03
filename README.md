# cjsh
An experimental shell based on Python. To run it, run:

$ git commit https://github.com/CJSHayward/cjsh.git
$ cjsh/cjsh

![A terminal session showing the shell](cjsh.png)

## Batteries included

CJSH comes with full Python power. Indent by one or more tabs (four spaces are
considered a tab), and you are no longer issuing individual shell commands;
you're programming in Python.

Drop the initial tabs and a shell line will be included in your code, *with
variable interpolation*.

A blank line terminates the Python or mixed block.

Please note that programming your ~/.cjshrc file can be very useful.

## Only say one thing

In a standard shell, you can only run a program (or builtin, etc.) by
specifying the name of the command. In CJSH, you can:

* Give the name of a program and run that program.
* Give the name of a directory and change directory to that directory.
* Give the name of an editable file and load it in the appropriate editor.

If an appropriate candidate file is not found in the current directory, it will
be searched for in the directory heirarchy. This means that if you are in a
project directory, and a filename is unique, you should be able to give just
the filename, without a path, and open it in your editor.

## Not yet contributed (*Patches welcome!*)

* Tab completion
* Job control

