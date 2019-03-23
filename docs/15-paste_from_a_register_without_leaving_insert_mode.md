* Vim's yank and paste command usually works from normal mode but sometimes it is useful to execute them from insert mode
* <C-r>{register} command pastes the contents from the specified register into to current location of the cursor in insert mode
* <C-r><C-p>{register} command is smarter. It inserts text literally and fixes any unintended indentation
