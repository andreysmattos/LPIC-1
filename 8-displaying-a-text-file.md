# Displaying a text file

### Command `cat`:
Cat(concatenate) command is very frequently used in Linux. It reads data from the file and give its content as output. It helps us to create, view and concatenate files. So let us see some frenquently used cat commands.

```
$ cat file_name
```

1. To view contents of a file preceding with line numbers.
```
$ cat -n file3.txt
     1	Nome: Andrey Mattos
     2	Idade: 28
     3	Cidade: Novo Hamburgo
     4	Profissonal: DEV
```

2. Create a file and add content

```
$ cat > newfile
```
---

### Command `head`:
The `head`command prints the first lines of one or more files (or piped data) to standard output. By default, it shows the first 10 lines.

```
$ head /etc/passwd
```
1. Displaying Specific Number of lines.
```
$ head -n [number] file_name
```

I can also modify that option and get the same results, but use a shorter syntax:

```
$ head -2 /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
```

2. Displaying a specific number of Bytes
```
$ head -c [bytes] filename
```

3. Dispaying the file name tag
```
$ head -v file3.txt 
==> file3.txt <==
Nome: Andrey Mattos
Idade: 28
Cidade: Novo Hamburgo
Profissonal: DEV
```

---
### Command `tail`:

Print the last 10 lines of each file to the standard output.

```
$ tail file_name
``

1. Change number of lines
```
$ tail -n 15 file_name
```

```
$ tail -15 file_name
```

2. Monitor the file for changes and continuously output new data written to the end of the file.
```
$ tail -f file_name
```

