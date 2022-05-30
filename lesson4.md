# Working with large text

## How to search for any text match

Press `:` to enter Command mode:

* Type `/Foo` then press `ENTER` to search text `Foo` starting from cursor.
* Type `n` to search forward, next occurance of the same text.
* Type `N` to search backward, previous occurnace of the same text.

## Search the word under cursor

Navigate to the word under cursor, then press `*` to search forward, `#` to search backword.

## Search and replace text

Press `:` to enter Command mode and use the `:substitue` command:

* Type `:s/foo/bar/g` - Find each occurrence of 'foo' (in the current line only), and replace it with 'bar'.
* Type `:%s/foo/bar/g` - Find each occurrence of 'foo' (in all lines), and replace it with 'bar'.

See more on https://vim.fandom.com/wiki/Search_and_replace
