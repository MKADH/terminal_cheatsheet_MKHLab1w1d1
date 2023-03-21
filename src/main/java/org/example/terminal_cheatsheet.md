# Terminal Cheatsheet to use
### Basic Terminal Commands
* `mkdir` - create new directory
* `touch ` - create new file
* `cd` - change directory
* `ls` - list files inside specific directory
>Note: The command 'ls' can be used with varying degrees of detail;
> * `ls -l`: Lists the unhidden files & subdirectories inside a parent directory
> * `ls -a`: Lists all hidden/unhidden files & subdirectories inside a parent directory (hidden files and depositories are identified by a . in front of their names)
> * `ls -la`: Lists all files & subdirectories inside a parent directory in a table format
* `clear` - unclutters commands
* `pwd <filename>` - Checks current file location
* `rm <filename>` removes files
* `open <filename>` - opens a specific file
* `mv` - moves files from one repository to another
### Basic Git Commands:
`git config --global` essentially is just a git identification tool for commits'
>`git config --global user.name "Sam Smith"` - Configure author name

>`git config --global user.email sam@example.com` -Configure email address

`git init` - Create a new local depository

`git add <filename>` - Adds file names (as long as they are written after the commands)

`git commit` - Commits changes to local (but not remote) repository

> e.g: git commit -m "Commit message"


`git push` - send changes in the file to the remote repository (github)

`git status` - list the files that are modified or have yet to be added to get committed
`git log` shows list of committed files and their time of modification