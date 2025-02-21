# Kilo

The text editor is [antirez’s kilo](http://antirez.com/news/108), with some changes. It’s about 1000 lines of C in a single file with no dependencies, and it implements all the basic features you expect in a minimal editor, as well as syntax highlighting and a search feature.

To run the program simply open a bash terminal and run the kilo file with ```./kilo```

to edit the file adjust the kil.c file using any text editor and compile with the ```make``` command

Controls:
```
CTRL-S: Save
CTRL-Q: Quit
CTRL-F: Find string in file (ESC to exit search, arrows to navigate)
```

Systems operating kilo require no dependencies.

Kilo was written by Salvatore Sanfilippo aka antirez and is released under the BSD 2 clause license.
