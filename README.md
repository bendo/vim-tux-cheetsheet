# vim-tux-cheetsheet
Mostly used vim and tmux cheatsheet

## VIM

Ctrl + w - binding

### Navigation
* gg - go to the first line of the document
* G - go to the last line of the document
* 5G - go to line 5


### Files
* :bn - go to the next buffer
* :bp - go to the previous buffer

### Editing
* u - undo
* Ctrl + r - redo
* . - repeat last command
* yy - yank (copy) a line
* dd - delete (cut) a line
* D - delete (cut) to the end of the line
* 1,10 y -- copy from , to line number 

### NERD tree
* Binding. - : NERDtree
* add file - m + a and file name

### Remove delay in switch between Normal and edit mode
set timeoutlen=1000 ttimeoutlen=0

## TMUX

Ctrl + b - key binding
tmux kill-server - kill all server


### Plane split
* Ctrl+b " - split pane horizontally.
* Ctrl+b % - split pane vertically.
* Ctrl+b arrow key - switch pane.
* Hold Ctrl+b, don't release it and hold one of the arrow keys - resize pane.
* Ctrl+b c - (c)reate a new window.
* Ctrl+b n - move to the (n)ext window.
* Ctrl+b p - move to the (p)revious window.

### Save /restore session
* Ctrl+b + Ctrl+s - Save session
* Ctrl+b + Ctrl+r - Restore session
