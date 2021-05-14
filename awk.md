# awk

* The awk command is used to perform the specific action on the text as directed by the program statement. 
* Using the BEGIN keyword with awk command specifies that awk will execute the action as denoted in begin once before any input lines are read.
* The command to append the text is provided in the BEGIN section, hence awk command will execute it once it reads the input lines.
* Reference: https://www.linuxfordevices.com/tutorials/linux/append-text-to-the-end-of-a-file-in-linux

```awk 'BEGIN{ printf "TEXT" >> "filename" }'```
