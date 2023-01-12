## Topic 1: The Shell

- `~`   ==> `/home` while `/` ==> `root`
- `$` tell you that you are not the root user while `#`  means you are the root
  - the way to be acted as the root is `sudo su` 
  - then authenticate your password you can have the power of the root.
  - if you want to quit and react as the user , type the keyword `exit` 
- `date`  ==> show the current time in your computer 
- `echo "string"`==> input the "string" into the standard output and then output on the screen of the shell.
- if u wanna input the name with whitespace, you can use `\` like `my\ photo`, or input the string by `"content"`like `"my photo"`
-  `$PATH` ==> environment variables
- `pwd` ==> display the current working directory,`.` refers to the current directory, and `..` to its parent directory:
- `ls` ==> show the what lives in the given directory
- `ls --help`  gives us a bunch more information about how to use the `ls`  command, and the `ls` command can be replaced by any other command.
- `ls -l ` show the details about the files or directory in the given directory
- `mv`  ==> rename/move a file and the parameters are `mv "target file" "target position and name"`
- `cp`  ==> copy the file and the rest is like `mv`
- `rm`  ==> remove the target file
- `rmdir` == > remove the target repository only when the repository is empty!
- `man` ==> show you its manual page and press `q` to exit
- `< file `  and `> file` ==> rewrite the input and output streams of a program to a file respectively
- `cat` ==> prints the contents of each of the files in sequence to its output stream,when `cat` is not given any arguments, it prints contents from its input stream to its output stream 
- `>>` ==> append to a file
- `|` ==> as a pipe and it can make the output of the commands on the left of the pipe as the input for the commands on the right of the pipe.
- `tee` ==> copy standard input the each FILE and also to standard output
- `xdp-open` ==> open the file with the best corresponding tools 

