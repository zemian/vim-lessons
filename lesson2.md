# The 3 common modes in Vim

1. The Normal(Read) Mode: When you first enter VIM, it is in this default mode. You can move cursor around in this mode, but not able to enter text! Pressing `ESC` key will always get you back to Normal mode. When you are in this Normal mode, you may navigate the content of your document using cursor moving keys: Press `h` will move cursor to left, `j` down, `k` up, and `l` to the right.

	NOTE: You always want to be in Normal Mode before entering into other modes!

2. The Insert Mode: Press `i` to change to this mode. When you are in this mode, all your keystrokes are used to enter text. The `h` will not go left of cursor anymore, but actually enter the value of `h` into the document. When you are done typing, press `ESC` to exit the Insert mode.

3. The Command Mode: Press `:` to change to this mode. Once you are in this mode, you will see a line on bottom of screen starts with `:` and it is waiting for you to type a command follow by ENTER to execute it. Vim has many command you can use. One important command is `quit`, which can also be shorten to `q` to exit Vim. If you modified the document, and still want to exit anyway, you can append exclamation mark like `q!` to quit without saving. Another very useful command is `:help`. It will open a help document (in split windows) that shows you how to use Vim. You may type `:q` to exit the help. You can narrow the help with a specific topic, command or keyword to search for help. For example `:help i` will tell you it is used to enter INSERT mode.


## Jump around Vim with Range

Many Vim commands support a range value that let you repeat the command several times quickly. For exmaple if you type `5j` in Normal mode, it will move 5 lines down from your current cursor!

Later when you learn more of other commands, keep in mind that you can prefix with a number, or
range to apply to the command! Example, `5yy` will yank/copy 5 lines of text, or `3dd` will delete
3 lines of text etc.

One often command to navigate in a large text file is to jump to beginning of the file with `gg`, or
`GG` to the end of the file! You may also jump to begininig of the line with `0`, or `$` to the end of current line.


## Exercise1: Create a new text file, save and exit

Type this command to start Vim

	vim hello.txt

Press `i` to enter into INSERT Mode, then type `Hello World`

Press `ESC` to exit INSERT mode back to Normal Mode, then Press `:` to enter Command Mode

Type `wq` to save and exit the Vim.

Extra: Try to exit Insert mode, navigate after the word `Hello`, then press `i` to insert another new word.


## Exercise2: Open an file and navigate the cursor


Type this command to start Vim

	vim

You should be in default Normal mode. (NOTE If you are in doubt, just press ESC)

Press `:` then type `help` to open the help document.

Now Press `h`, `j`, `k` or `l` key to navigate the cursor around the document.

Press `:` and type `q` to exit the help.

Press `:` and type `q` again to exit Vim.
