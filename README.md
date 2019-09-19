# Vim = Vi+Improved
1. What's `vi`?
	`vi` is a text editor. It was originally written in 1976, for the
	first BSD release. The main goal was to add a full-screen visual
	mode to the famous single-line `ex` editor. `vi` is defined by the
	UNIX standard, and thus, every conforming OS has `vi`.
2. What is `vim`?
	It's a `vi` clone but with a lot of improvements.
3. What is `neovim`?
	`Neovim` is a refactoring of `vim`. It has a lot of cool features
	such as internal terminal support and asynchronous capabilities.

## Goals of this talk
1. To **not** turn you into Vim Masters
2. To help you understand vim documentation.
3. To introduce you to basic vim concepts.

## 1. History of Vim
	`vi` was originally written by Bill Joy. `vim` was created by
	Bram Moonlear and first released in 1991. Bram remains the project
	lead to this day.

## 2. Terminology
1. Commands - `:help`
2. Keystrokes - <F1>
3. [Buffers](https://vim.fandom.com/wiki/Vim_buffer_FAQ)
	Buffers are the files that you have opened which vim is holding in
	memory
5. "Tab"page
4. Windows/Splits - windows == splits
6. Modes

## 3. The three main parts of the "editing" process
1. Navigate/move/read through a file.
2. Add content/remove content/edit content of a file.
3. How to select content in a file.
4. Navigate through/jump between multiple files.

## 4. How to move through a file
Refer this --> usr_03.txt

## 5. Add content/remove content/edit content of a file.
Refer this --> usr_24.txt

## 6. How to select content in a file.
Refer this --> visual.txt

## Things to cover
1. Macros
2. Search and replace (include regex example)
3. Indents and folds

## Things to do
1. `python2.7 screenkey.py`
2. `alias vim-talk="vim -u talk-vimrc"`

## References

[1]: https://github.com/mhinz/vim-galore 

[2]: http://vimcasts.org/ <tab> `wget -nd -np -r -erobots=off -N -c -A '*.m4v' http://media.vimcasts.org/videos/`


