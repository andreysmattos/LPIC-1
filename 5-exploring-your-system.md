# Exploring your system

### Command: `uname`
The command `uname` display the information about the system.

```
$ uname
Linux
```

1. `a` option: It print all the system information in the following order: Kerner name, network node hostname, kernel release date, kernel version, machine hardware name, hardware platform.
```
$ uname -a
LinuxLinux pop-os 6.2.6-76060206-generic #202303130630~1689015125~22.04~ab2190e SMP PREEMPT_DYNAMIC Mon J x86_64 x86_64 x86_64 GNU/Linux
```

2. `-s` option: It prints the kernel name.
```
$ uname -s
Linux
```

3. `-n` option: It prints the hostname of the network node (current computer)
```
$ uname -n
pop-os
```

4. `-r` option: It prints the kernel release date.
```
$ uname -r
Linux6.2.6-76060206-generic
```

5. `-v` option: It prints the version of the current kernal
```
$ uname -v
#202303130630~1689015125~22.04~ab2190e SMP PREEMPT_DYNAMIC Mon J
```

6. `-m` option: It prints the machine hardware name:
```
$ uname -m
x86_64
```

---

### Bash
Bash, short for Bourne-again shell, is a command-line shell and scripting langauge used on Linux, macOs, and other unix-like operating system.

### Features of Bash
- **Command-line editing**: Bash allows users to edit their commands using the arrow keys and other editing keys, making it easier to correct mistakes and modify commands.
- **Command history**: Bash keeps a history of the commands that have been entered, making it easy to recall and reuse previous one when needed.
- **job controll**: Bash allows users to run multiple commands in the background and switch between them, making it easier to manage and monitor long-running tasks.
- **shell scripting**: bash inclused a powerful scripting language that allows users to automate tasks and perform complex operations.
  
1. `bash --version`

```
$ bash --version
GNU bash, version 5.1.16(1)-release (x86_64-pc-linux-gnu)
Copyright (C) 2020 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>

This is free software; you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.
```

### How to find quickly a Bash command type?
The `type` command is used to find out if command is builtin or external binary file.

A simple example of using the bash `type` bultin would be with the `echo` command which comes as a bash shell builtin but is also frequently found as a binary in `/bin/echo`. **Depending on your system, the two `echo` commands may behave differently**

```
$ type echo
echo is a shell builtin
```

```
$ type mv
mv is /usr/bin/mv
```


