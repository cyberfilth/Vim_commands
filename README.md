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

### Use VIM as a hex editor
```
:%!xxd       # View file as hex editor
:%!xxd -r    # Go back to normal mode before saving any changes
```

### Get Word Count in current file (require wc to be installed)
```
:w !wc -w
```
