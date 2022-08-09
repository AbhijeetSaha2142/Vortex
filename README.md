# Vortex
This is a modern text editor written in OCaml that features cursor control, word completion, find and replace, and file saving.

# Build & Run
Make sure the dependencies listed in INSTALL.md are installed, then simply build
the text editor

```console
$ dune build
```
and run it

```console
$ make run
```

# Controls
Click on the popup window to start typing and have your text show up in the terminal. Use the arrow keys to navigate your cursor. To complete a word to the given suggestion press tab. To save a file press either left or right ctrl and follow the prompts for naming the file. To find and replace a word, press left or right alt and follow the prompts. To exit Vortex press escape.
