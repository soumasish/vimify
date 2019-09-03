# Quickest Guide to Getting Strated with Vim

Vim in essence has two modes - `INSERT` and `NORMAL`. You enter text in `INSERT` mode, everything else you do in `NORMAL` mode. When you open vim you land in the `NORMAL` mode; to get to `INSERT` mode type `i`, and vim is ready to insert right where you are, or `o` and vim will create a new line and put the cursor at the beginning of the new line for insertion. To escape out of insert mode type `esc` or `Ctrl + C`
### Convetions
- If a key includes a `+` it means the two have to typed together, like `CTRL + F`
- If it doesn't then they have to be typed in sequence, like `dd`.

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

### Delete/Change
|#|Action|Key|
|-|:-----|:--|
|1|Delete word|dw|
|2|Delete line|dd|
|3|Delete sentence|d)|
|4|Change word|cw|
|5|Change sentence|cc|
|6|Undo|u|

### Copy & Paste
|#|Action|Key|
|-|:-----|:--|
|1|Copy word|yw|
|2|Paste word|P|

### Move between buffers
|#|Action|Key|
|-|:-----|---|
|1|Open a new file in the same window|:new filename|
|2|Move between buffers|Ctrl+w w|
|3|Close a buffer|Ctrl + w c|
|4|Edit a file|:e filename|
|5|Open a directory|:e .|
|6|Open a file in a directory|Select the filename and Enter|
|7|Delete buffer|:bd <name>|
|8|Next buffer|:bn|
|9|Previous buffer|:bp|
|10|Specific buffer|:b <filename>|
|11|All buffers|:ls|

