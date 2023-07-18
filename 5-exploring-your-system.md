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
