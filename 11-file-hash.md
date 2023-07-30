# Ensuring Data Integrity
There are times where you may wish to distribute a file to someone else, and you want to be sure that the recipent ends up with a true copy of the original file.

### Checksum
A checksum is a value derived from a mathematical computation, based on a cryptographic hash funciton, against a file.


Once you download a file you would then compare the checksum of the file that was downloaded against a checksum value that was provided you.

Example:
```
$ sha256sum person.txt 
91b6ed620e79ade945d252401b9c1f06509b67d9ea4eca55e0b64d00b7b1362e  person.txt
```

We can do this with the same sha256sum command and redirect the output to a file:

```
$ sha256sum person.txt > sha256.txt
```

Now, to verify the person.txt file, we just use the same command and supply the filename that contains our checksum value along with the -c switch:

```
$ sha256sum -c sha256.txt 
person.txt: OK
```



