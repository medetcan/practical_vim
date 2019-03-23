* Command-Line allows us to execute ex command, a search pattern, or an expression
* :[range]delete[x] -> delete specified lines of texts into the register x
* :[range]yank[x] -> copy specified lines of text into the register x 
* :[line]put[x] -> paste specified content from the register below to the specified line
* :[range]copy{address} -> Copy the specified lines to below the line specified by {address}
* :[range]move{address} -> Move the specified lines to below the line specified by {address}
* :[range]join -> Join the specified lines
* :[range]normal{commands} -> execute normal mode commands on each specified line
* :[range]substitute/{pattern}/{string}/[flags] -> Search and replace tge occurences of the text on specified lines
* :[range]global/{pattern}/[cmd] -> Execute the Ex command [cmd] on all specified lines where the {pattern} matches
* ":" command switches us into the commad line mode
* "/" or "<C-r>=" keys are also allow us to use the capabilities of the command line mode 
* :edit ex command allows us to read a file
* :write ex command allows us to write to a file
* :split ex command command allows us to split the current window
* :tabnew open up a new window
* :prev/next switch beetween tabs
* We can use <C-u> command in command line mode to delete back to the begining of the line
* <C-w> command can be used in command line mode to delete bac to previous word
