# Command line history


### Command `history`:
The `history` command show a list of the commands entered since you started the session. The joy of the `history` is that now you can replay any of them by using a command suc as: 

```
$ !3
```

The `!3` command at the prompt tells the shell to rerun the command on line 3 of the history list. 


### Removing history
The history file is stored in a file that youc an modify, as well. Bash users find it in their home directory as `.bash_history`

If you want to delete a particular command, enter `history -d <line number>`. Toclear the entire contents of the history, execute `history -c`. 

### Notice
If I display my history using `history` command, notice that it doesn't extactly contains the same commands as when I display the history file using `cat` command. This is because the history command display what is called the history list, and the history list exists in memory until you log out.
