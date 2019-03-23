* Many ex commands accept a range to act on we can specify either a line number, a mark or a pattern for a range
* If we enter solely a number in command line mode, vim will interpret it as a line number and move our cursor to the specified line
* "." symbol represents the current line when used as a range
* "%" symbol represents the whole file when used as a range
* We can specify a range using visual selection when you make a visual selection and then switch to command line mode cryptic text will appear as a range
* Vim also accepts a pattern as an adress for an ex command
* We can use offsets on a given range such as /<html>/+{offset}/<\/html>+{offset}
