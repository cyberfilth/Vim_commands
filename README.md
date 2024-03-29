# Vim commands
A list of Vim commands that I find useful.

### Add a line break
```r [enter]```


### Joins a line to the one below it
```J```

### Add / remove indentation
```>>``` and ```<<```\
Indentation is set by shiftwidth, the default is 8 spaces


### Collapse / fold code
Select code block in visual mode then
```zf             # Fold the selected code
za             # Fold / unfold text at cursor position
zM             # Fold all foldable code
zR             # unfold all foldable code
:mkview        # Save fold information before saving file
:loadview      # Load fold information after loading file
```

### Autocomplete abbreviations
```
:ab linux GNU/Linux  # When 'linux' is typed it will autocorrect to GNU/Linux
:ab                  # List all abbreviations
:unab linux          # Remove 'linux' from abbreviations
:abc                 # Clear all abbreviations from memory
```

### Split windows
```
:sp         # Split window horizontally
:vs         # Split window vertically
CTRL+w < >  # Change width of window
CTRL+w - +  # Change height of window
```

### Move a window
```
CTRL+w H    # Move active window to the Left of the screen
CTRL+w L    # Move active window to the Right of the screen
CTRL+w J    # Move active window to the Bottom of the screen
CTRL+w K    # Move active window to the Top of the screen
```

### Use VIM as a hex editor
```
:%!xxd       # View file as hex editor
:%!xxd -r    # Go back to normal mode before saving any changes
```

### Get Word Count in current file (require wc to be installed)
```
:w !wc -w
```

### Copy text to system clipboard
Select text in visual mode then
```
"+y
```

### Paste text from system clipboard
```
"+p
```

### Multi-line insert - like commenting out code
- CTRL + v top go into visual mode
- Highlight the lines you want to change
- SHIFT + i and type in the text you want
- ESC (then wait a second)

### Multi-line edit
- Search for the word to change
```
/searchString
```
- press ENTER
```
cgn
```
- Stands for Change. Get the string. Next match
- Type in replacement word
- ESC
- Press . to change the next match

### Delete everything inside quotation marks
```
di"
```
