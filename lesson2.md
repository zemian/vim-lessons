## The 3 common modes in Vim

1. The Normal(Read) Mode: When you first enter VIM, it is in this default mode. You can move cursor around in this mode, but not able to enter text! Pressing `ESC` key will always get you back to Normal mode. When you are in this Normal mode, you may navigate the content of your document using cursor moving keys: Press `h` will move cursor to left, `j` down, `k` up, and `l` to the right.

	NOTE: You always want to be in Normal Mode before entering into other modes!

2. The Insert Mode: Press `i` to change to this mode. When you are in this mode, all your keystrokes are used to enter text. The `h` will not go left of cursor anymore, but actually enter the value of `h` into the document. When you are done typing, press `ESC` to exit the Insert mode.

3. The Command Mode: Press `:` to change to this mode. Once you are in this mode, you will see a line on bottom of screen starts with `:` and it is waiting for you to type a command follow by ENTER to execute it. Vim has many command you can use. One important command is `quit`, which can also be shorten to `q` to exit Vim. If you modified the document, and still want to exit anyway, you can append exclamation mark like `q!` to quit without saving. Another very useful command is `:help`. It will open a help document (in split windows) that shows you how to use Vim. You may type `:q` to exit the help. You can narrow the help with a specific topic, command or keyword to search for help. For example `:help i` will tell you it is used to enter INSERT mode.
