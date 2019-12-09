# Vim commands
A list of Vim commands that I find useful.

##Add a line break
```r [enter]```

Joins a line to the one below it
```J```

Add / remove indentation
```>>``` and ```<<```

set an abbreviation, everytime you type 'linux' it will autocorrect to 'GNU/Linux'
```:ab linux GNU/Linux```
A useful example would be ```:ab teh the```

clear abbreviations
```:abc```


:sp
Split window

:vs
Vertical split

CTRL+w < >
change width of window

CTRL+w - +
change height of window

:%!xxd
use VIM as a hex editor, :%!xxd -r go back to normal mode before saving any changes
