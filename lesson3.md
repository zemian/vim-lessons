## How to insert text efficiently

When entering Insert mode, you can use different command to quickly position the cursor before inserting new text.

Press `i` to insert right at the cursor.
Press `a` to insert right after the cursor.
Press `o` to insert a line below.
Press `O` to insert a line above.

## How to quickly navigate line 

When you are in Normal mode, you can move quicker with the following commands:

Press `0` to go beginning of the line.
Press `$` to go end of the line.
Press `CTRL+u` to go half screen up.
Press `CTRL+d` to go half screen down.

NOTE: If you are in middle of editing text (Insert Mode), you need to press `ESC` to go back Normal mode.

## Quick Edit between Insert/Normal modes

These commands you often would do while inserting text, then press ESC to exit, perform commands then press `i` to get back to editing.

Press `dh` to delete one charater left
Press `dl` to delete one charater right
Press `dw` to delete one one word toward right
Press `dd` to delete the line
Press `dt<char>` to delete until a char is found. (eg: char=")
Press `d$` to delete until end of line
Press `r<char>` to replace single character
Press `u` to undo the previous command
Press `CTRL+r` to redo the previous command

## Cut and Paste

Again, ensure you are in Normal mode first:

Press `yy` to copy (yank) a line
Press `p` to paste a line back in below the cursor.
Press `P` to paste a line back in above the cursor.
Press `dd` to delete a line

Press `ma` mark position and assign to marker 'a'
Press `y'a` copy (yank) text until marker 'a'
Press `d'a` delete (yank) text until marker 'a'
