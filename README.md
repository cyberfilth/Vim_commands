# Vim commands
A list of Vim commands that I find useful.

### Add a line break
```r [enter]```

### Joins a line to the one below it
```J```

### Add / remove indentation
```>>``` and ```<<```

### Autocomplete abbreviations
```
:ab linux GNU/Linux  # When 'linux' is typed it will autocorrect to GNU/Linux
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
