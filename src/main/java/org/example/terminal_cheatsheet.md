# Terminal Cheatsheet to use
### Basic Terminal Commands
* `mkdir` - Create new directory
* `touch ` - Create new file
* `cd` - Change directory
* `ls` - List files inside specific directory
>Note: The command 'ls' can be used with varying degrees of detail;
> * `ls -l`: Lists the unhidden files & subdirectories inside a parent directory
> * `ls -a`: Lists all hidden/unhidden files & subdirectories inside a parent directory (hidden files and depositories are identified by a . in front of their names)
> * `ls -la`: Lists all files & subdirectories inside a parent directory in a table format
* `clear` - Unclutters commands
* `pwd <filename>` - Checks current file location
* `rm <filename>` Removes files
* `open <filename>` - Opens a specific file
* `mv` - Moves files from one repository to another
### Basic Git Commands:
`git config --global` Essentially is just git's way of identifying authors trying to commit files
>`git config --global user.name "Sam Smith"` - Configure author name

>`git config --global user.email sam@example.com` -Configure email address

`git init` - Create a new local depository

`git add <filename>` - Adds file names (as long as they are written after the commands) to the staging to be committed

`git commit -m "random comment"` - Commits changes to local (but not remote) repository. Usually requires a comment added with it for explanation

> e.g: git commit -m "manchester united season statistics draft"


`git push` - Send changes in the file to the remote repository (Github)

`git status` - List the files that are modified or have yet to be added/staged to get committed

`git log` Shows list of committed files and their time of modification

> ### Purpose of `.gitignore`
> If `git status` is entered into a terminal, it shows all files that are untracked files and or files to be committed. If the author wishes to have certain untracked files completely ignored by git, to the point of not even showing up on the list of untracked files (in essence, incognito), they would put it into what's known as a `.gitignore` file. This is useful for when multiple people are working on code and dont want certain files in different depositories to override each other (or clutter it up). Each line in a `.gitignore` file represents a pattern that gets cross checked with multiple sources in the directory tree before ignoring a path. This repository has an example `.gitignore` file that has made git completely ignore pom.xml.

>`.gitignore` cannot affect its parent folder which is why the `.idea` file is still tracked when `git status` is invoked


