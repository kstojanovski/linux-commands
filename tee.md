# tee

* The tee command is used to read the standard input and writes it to the standard output as well as files too. 
* ```-a``` option will not overwrite the content but will append it to the file.
* Reference: https://www.linuxfordevices.com/tutorials/linux/append-text-to-the-end-of-a-file-in-linux

```cat "filename1" | tee -a "filename2"```
