 * Make change -> . | u
 * Scan line for the next character -> f{char}/t{char} | ; , -> difference beetween t{char} and f{char} is t{char} moves cursor to the one column back from the matched character
 * Scan line for the previous character -> F{char}/T{char} | ; , 
 * Scan the document for the next match -> /pattern<CR> | n N
 * Scan the document for the previous match -> ?pattern<CR> | n N
 * Perform substitution -> :s/pattern/replacement | & u
 * Execute sequence of changes -> qx{changes} | @x u
 * @: command can be used to execute last ex command
