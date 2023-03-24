# CMD Commands

| Command | Description |
| - | - |
| `cd (folder) \ (folder) ` | Changes directory, if the folder name contains space enclose it with double-quotes |
| `cd ..\..` | Traverses backwards (reverse) from the current directory (folder) |
| `pwd` | Prints the current working directory |
| `ls` | Lists all the content at once from the current directory (folder) |
| tab | Autocompletes commands (gives all the possible options to consider) |
| `dir` | Lists the contents from the current directory in detail (gives the total number of directories and files) |
| `dir (remaining path to that directory from the current directory)` | Same as above, the difference is that it doesn't changes the path of the current directory |
| `dir /a` | Same as `dir`, additonally displays all the hidden files where **/a** is an option |
| `cls` | Clears the screen |
| `dir *.(file extension)` | Same as `dir` but this will list only all the files that have the given file extension |
| &#8593; / &#8595; | Navigating history of commands |
| `(file)` | Opens the file of the specified name using the default application (make sure to surround the file name having spaces with double-quotes) |
| `(command) /?` | Describes briefly about the command specified (list of options, description, etc), also known as the **help** command |
| `mkdir (directory)` | Creates a directory |
| `rmdir (directory)` | Removes the given directory |
| `rmdir /s (directory)` | Deletes all the contents of the directory (folder), where **/s** is an option |
| ctrl + (&#8592; / &#8594;) | Traverses word by word |
| ctrl + c | Force stopping the program |
| `(drive)` | Jumps to the specified drive |
| `tree` | Shows hierarchical relationships between folders of the current directory |
| `echo > (file)` | Creates a new file in the current directory |
| `rm (file)` | Removes a file in the current directory |
| `attrib` | Displays the file attributes |
| `del (file) (file)` | Deletes a file or files in the current directory |
| `type (file)` | Reads the content of the file from **CMD** |
| `rename (folder 1) (folder 2)` | Renames **folder 1** to **folder 2** |
| `move (folder 1) (folder 2)` | Moves **folder 1** to **folder 2** provided both are accessible from the current directory, else give the absolute path of the folders |
| `copy (file) (folder)` | Copies the given file to the specified folder provided both are accessible from the current directory, else give the absolute path of both|
| `xcopy (folder 1) (folder 2)` | Copies the **folder 1** to **folder 2** (all files, sub-folders, etc) provided both are accessible from the current directory, else give the absolute path of both |
