# Sort

Sort is a command-line utility in Linux that helps you to sort the data in a file line by line. It has a lot of options that allow you to arrange the record in a specific order. It supports sorting, in reverse order, by month, by number, alphabetically, and more.


```
$ echo -e "cebola\nalface\nalho\nkiwi\nma
 a\namora\nmoranga\nameixa" >> items.txt
```

```
$ cat items.txt 
cebola
alface
alho
kiwi
maça
amora
moranga
ameixa
```

```
$ sort items.txt 
alface
alho
ameixa
amora
cebola
kiwi
maça
moranga
```


