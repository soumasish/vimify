# Vim Guide

Vim in essence has two modes - `INSERT`, when you're writing text, or Normal when you're moving around to find something to write or edit. When you open vim you land in the `NORMAL` mode. To insert something type `i`, and vim is ready to insert right where you are, or `o` and vim will create a new line and put the cursor at the beginning of the new line for insertion. To escape out of insert mode type `esc` or `Ctrl + C`

### Moving around
|#|Action|Key|
|-|:-----|:--|
|1|Next word|w|
|2|End of next word|e|
|3|Previous word|b|
|4|End of the previous word|ge|
|5|Next sentence|)|
|6|Previous sentence|(|
|7|Next paragraph|}|
|8|EOF|G|
|9|BOF|g|
|10|Next page|Ctrl + F|
|11|Previous page|Ctrl + B|
|12|Specific line|line number|
|13|End of line|$|
|14|Beginning of line|0|

### Search
|#|Action|Key|
|-|:-----|:--|
|1|Foward|/|
|2|Next ocuurence|n|
|3|Backward|?|
|4|Next occurence of current word|*|
|5|Previous occuremnce of current word|#|

