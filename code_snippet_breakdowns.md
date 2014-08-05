###10 Command Line and Git Commands I have Trouble remembering

<span style="color: red;">For the purposes of the commands below lets assume we have a file named ryan.txt</span>

Command		| Description
------------|------------
`ENV` 		| shows the environmental variables used by bash. (examples include user name and can include passwords)
`rm -r`		|  this removes a file.  The `-r` is only needed for directories.  **Be careful with this command**
`cp` 		| copies a file.
`mv` 		| moves a file.
`>`			| allows to to implement commands to a file.  This may delete the existing comments of a file.  Example: `echo "say hello" > Ryan.txt`
`>>`		|allows to to implement commands to a file.  This as opposed to ">" will keep the contents of a file.  Example: `echo "glad say hello from above is still here" > Ryan.txt`
`git init`	| initaites init on a directory or file and allows us to track changes.
`git add`	|  this command puts files into a format where we can use the commit command.  Note that files will change color in the terminal window
`git commit -m`| this commits the changes to the log file.  the `-m` allows us to provide comments directly in the command line.
`git log`	| pulls up a list changes with a unique id.  We can copy and past this id into terminal to use diff
`git diff` |shows the changes between versions of the same file.


#test for Github tracking
