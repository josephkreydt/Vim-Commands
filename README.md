# Vim-Commands

These are my favorite Vim commands

### Joe's VIM Cheat Sheet

esc - switch command mode 
i - switch insert mode 

a - switch to insert mode, but AFTER cursor, not before it 

I - switch to insert mode and move cursor to beginning of line 

A - switch to insert mode and move cursor to end of line 

o - switch to insert mode and create a blank line below the current one 

O - switch to insert mode and create a blank line above the current one 


esc + 
	:q! - quit without saving
	:wq - save and then quit - can also do ZZ
	:w - save
	:saveas ~/filename.txt - save-as
	u - undo
	CTRL+r - redo
	[num]u - undo the past [num] changes (ex: 10u undoes past 10 changes)
	y - yank (copy)
	yt[char] - yank to whichever [char] you specify
	d - cut or delete (they're the same)
	p - paste
	P - paste before the cursor
	gg - jump to top of file
	G - jump to bottom of file
	H - go to top (higher) of current page/window
	L - go to bottom (lower) of current page/window
	M - go to middle of current page/window
	/[text] - search for whatever [text] you specify
		n - jump to the next instance of the [text]
		N - jump to the previous instance of the [text]
	0 - move cursor to beginning of line
	$ - move cursor to end of line
	CTRL+SHIFT+U - move cursor up a few lines
	CTRL+SHIFT+D - move cursor down a few lines
	CTRL+SHIFT+B - move cursor up a page
	CTRL+SHIFT+F - move cursor down a page
	j - move cursor down a line
	k - move cursor up a line
	h - move cursor left one character
	l - move cursor right one character	
	^ - move to the first non-blank character in the line
	C - delete everything after the cursor and enter insert mode 
	S - delete the entire line you're on and enter insert mode
	:line_number [num] - move to the line [num] you specified
	x - delete the character under the cursor
	X - delete the character before the cursor
	D - delete to the end of the line
	:set spell - turn on spell-checker
	:set nospell - turn off spell-checker
	:bo term - splits screen and puts a terminal window on bottom
		CTRL+d twice - closes the terminal window
		CTRL+w - switch from terminal to vim and back
	zz - when you're at the bottom of the screen, this will add a bunch of virtual lines so the lowest text in the file is not at the very bottom of the screen
	CTRL+E - similar to zz, but only adds one virtual line at a time
	
	combos
		dd - delete entire line
		dt[char] - delete to whichever [char] you specify
		yy - yank entire line
		ct' - change everything up until the next ' character
		ct[char] - change everything until the next instance of the [char] you specified
