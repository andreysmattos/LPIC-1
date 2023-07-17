# Basic comamnd line

# Command: `tty`
The most basic use of the tty command is to display the name of the current terminal.

```
$ tty
/dev/pts/0
```

This command tells you what file name connected to standard input. The term **pts** is the abbreviation for pseudo. If you run the command directly on a real TTY you have the following:

```
$ tty
/dev/tty1
```

# Command: `whoami`
It displays the username of the current user when this command is invoked.

```
$ whoami
andrey
```


# Command: `pwd`
Display the path name of the working directory. 
current working directory = present working directory

# Command: `ls`
Display the contents of a directory.


# Command: `exit`
exit command in linux is used to exit the shell where it is currently running.

# Command: `cd`
The `cd` (change directory) is pretty simple. It permits you t switch directories from one to anohter via terminal
- `~`: It always point to the home directory
- `.`: It represent the current working directory.
- `..`: It represents back to the parent directory
- `-`: It quickly gets back to your last working directory and prints the directory path.