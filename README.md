# Ticket-Generator
A project from Frontend Menthor, after completing the frontend, i hope to complete its backend and deployment sides as well using AWS. mainly to get hands on NUXT practice

### Learning to use VIM:
well now since this is my practice project after all, im learning vim as well (its mainly to use git rebase interactive) and i am currently editing this file using vim.
Commands:

:q for quit, vim <filename> to open the file in vim editor
there are modes to vim editing, so "normal" is what it opens with, cant edit. to edit, press "i" which opens the "insert" mode, can edit here. then, press "escape" to go to normal mode and press "colon" to go to command mode and type command like q for quit, wq for write and then quit, q! for quit without saving etc 
and then "capital A" is append mode (technically insert) but it gets you to the end of the line when this triggered.
to undo, you escape and go to normal mode and then press "u" to undo changes
to go to beginning of line, press "0" zero and to go to end of line, press "$" sign

everytime you are using vim, you are working with atleast 1 buffer, think of it as an open empty file
In normal mode, you can delete a character by pressing "x"
delete an entire line by pressing "dd" twice
then press "u" to undo these changes
in normal mode, can also move the cursor from hjkl keys, along with arrow keys, helps with "touch type", less muscle movement
can also use :r <filepath> while in another file's normal mode to append the filepath's contents to where your cursor is in the current file
if do :w <newfilename> then the changes are saved to a new file
in vim file, press ":!" ls and ls command will be executed, so can execute linux commands like this.

Buffers: can add text from a file into buffer using the :r command. 
now, to see its usefulness, for example, in a current file (which is a buffer), you do :e <newfilepath> where :e means edit, this opens the newfilepath in a separate "buffer" window where just the contents of new filepath are open. now, you have 2 buffers. 
you can navigate between these buffers using :bp (buffer previous) and :bn (buffer next) commands, it is a circular list
in command mode, type ":enew" meaning edit new to open a empty new buffer

Visual Mode: opened by typing "v" on the normal mode. moving the cursor here highlights (selects) all the text from starting 
copy the selected text by typing "y" (yank) on the keyboard and "p" (put) to paste the text, the p works in normal mode.
also once selected, press colon and then "sort ui" to sort the selected lines alphabatecially, useful when finding something in a config file.

  
