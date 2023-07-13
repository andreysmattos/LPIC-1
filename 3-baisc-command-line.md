# Basic comamnd line

# Comando: `tty`
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
