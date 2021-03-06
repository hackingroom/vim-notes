# Doc - Luis

__   _(_)_ __ __
\ \ / / | '_ ` _ \
 \ V /| | | | | | |
  \_/ |_|_| |_| |_|

## What is vim?
  * vim > vi
  * Mode editor

## Basic stuff
  * $ vim filename
  * :o filename
  * :q
  * :w

## Basic VIM modes
 * NORMAL
 * INSERT
 * VISUAL

## Navigation
 * h,j,k,l
 * ^ or 0 - move to the start of the current line
 * $  - move to the start of the current line
 * gg - jump to the beginning of the file
 * G - jump to the end of the file

## Delete
 * x - delete the character under the cursor
 * dd - delete the current line
 * D or d$ - delete from the cursor to the end of the current line
 * d0 or d^ - delete from the cursor to the start of the current line

## Copy
 * yy - yankk the current line
 * y$ - yank from the cursor to the end of the current line
 * y0 or y^ - yank from the cursor to the start of the current line

## Paste
  p

## Searching
 * f-F
 * t-T
 * /  - Forward
 * ?  - Backward
 * *  - Word under cursor - forward
 * #  - Word under cursor - backward
 * n  - Next result, forward
 * N  - Next result, backward

## Commands = operator + motion
### Motions
  * w - Forward to the beginning of next word
  * b - Backward to the next beginning of a word
  * e - Forward to the next end of word

### Operators
  * c - Change
  * d - Delete
  * y - Yank

## Cool shit
   * vimrc
   * set -o vi

## Resources
  * $ vimtutor
  * http://vim-adventures.com/
  * :h :help
  * https://github.com/bronzdoc/dotfiles
  * http://www.slant.co/search?query=vim
