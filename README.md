# An Introduction to Board Design #
This repository presents a common place to store documents which have become
useful during the design process for a microcontroller board. Because the
project is still so young, we haven't even come up with a name for it.

## A Little About the Project ##
This microcontroller board will be the brainchild of two Computer Engineering
students from Michigan Technological University. It will be minimalistic,
versatile, with more built-in functionality than can be found on comparable
microcontroller boards. Most importantly, it's an experiment to prove that
board design is not necessarily the Holy Grail of computer engineering.

This repository will be updated as the project evolves. It will contain design
goals, boms, schematics and board design files, and potentially even software.

## Repository Workflow ##
Below is a description of the directory organization:
```
doc/	- Documents for the project, including internal documentation, user
		manuals, application notes, etc.
pcb/	- Schematic, PCB, and supporting files.
sfw/	- Software for the board, including device drivers, board-specific
		bootloaders, etc.
```
In general, files on the master branch should be considered to be working files.
As files are finished and released, they will be migrated to a `Release` branch.

<!--
This list is used by the bug tracker. Please make sure to format any with a
C-style comment opener ('/* ') followed by the word todo in caps and a colon.

To update the 'bugs' file, run the command 'b update.' This assumes that you
have the 'b' command correctly set in your .bash_aliases. A working example of
the 'b' command can be found in:
https://github.com/AmateurECE/Tools/blob/master/.bash_aliases

/* TODO: Draft Functional Description
-->
