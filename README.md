# vim-specman-log
Syntax highlighting for Specman (e) log files in VIM


Provides syntax highlighting for specman simulation log files in VIM.

Some of the highlighted elements are:

- Dates and times
- Common log level keywords like ERROR, INFO, DEBUG
- Numbers, booleans and strings
- URLs and file paths
- IP and MAC addresses
- SysLog format columns
- XML Tags

**Specman related:**

- DUT error
- assertion
- matlab run



## **Installation**

Put the following lines in ~/.vimrc file:

> au BufNewFile,BufRead *.log set filetype=log
> 
> au BufNewFile,BufRead *_log set filetype=log
> 
> au BufNewFile,BufRead *.LOG set filetype=log
> 
> au BufNewFile,BufRead *_LOG set filetype=log
