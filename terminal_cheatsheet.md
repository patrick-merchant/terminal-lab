# Terminal Cheatsheet
| Command | Description|
| ----------- | ----------- |
| *cd [folder]* | Change directory: e.g. cd [bnta]. Relative or absolute path |
| *cd* or *cd~* | Home directory |
| *cd-* | Previous directory |
| *..* | Move "up a level" from whatever folder you are in |
| *ls* | Lists (non-hidden) folders in directory |
| *ls -l* | Long list of (non-hidden) folders in directory (incl. info e.g. date last modified) |
| *ls -a* | Lists **all** files. Can be used in conjunction with *-l* e.g. *ls -al* |
| *open [file]* | Opens a file or launches an application |
| *code [file]* | Opens a file with VSCode |
| *cat [file]* | Concatenate to screen (print to terminal) |
| *mv [file] /[new file name]* | Move/Rename e.g. myfile.ad /tmp. Path to new file can be **Absolute** (e.g. Users/joebloggs/myfiles/my_file_2/ ) or **Relative** (e.g. ../my_file_2) |
| *cp [file] [dir]* | Copies file or directory (add -a or -r to copy all directory content (-r retains directory structure)) |
| *ditto -v [original file] [new file]* | Copies content of a directory into a new file (-v adds a verbose output for files copied) |
| *rm [file]* | Remove a file |
| *rm -i [file]* | Remove with confirmation |
| *rm-r [file]* | Remove directory and contents |
| *Tab* | Autocomplete files and folder names; if multiple options exist, continue pressing Tab to cycle through them |
| *sudo [command]* | Run command with the security privileges of the superuser |
| *nano [file]* | Opens the file using the nano editor. Leave with Ctrl + X |
| *clear* | Clears the screen |
| *touch [file]* | Creates a file and names it |
| *mkdir* | Make directory |
| *pwd* | Full path to working directory |
| *find [dir] -name [search_pattern]* | Search for files, e.g. find /Users -name "file.txt" |
| *whatis [command]* | Gives a one-line description of [command]
| *apropos [search-pattern]* | Searches for command with keywords in description |
| *man [command]* | Shows manual page for a command |
| *q* | Quits subscreen and return to Terminal |
| *exit* | Closes current session in Terminal. Particularly useful when using SSH through Terminal to access a remote machine | 

<br>

## Here is a screenshot of some basic terminal commands!

<br>

![A screenshot of some basic terminal commands!](https://raw.githubusercontent.com/patrick-merchant/terminal-lab/main/terminal_screenshot.jpg "Terminal Screenshot")
