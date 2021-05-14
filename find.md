# find

* Reference: https://stackoverflow.com/questions/6844785/how-to-use-regex-with-find-command

```find . -name "somefilename"```

* ```.``` - recursion
* ```-name``` - after this the file name needs to be added, widlcard can be also used.

```find . -name *.txt```
<br>
```find /home/user -exec grep -H "passwort" {} \;```
<br>
```find . -regextype sed -regex ".*/[a-f0-9\-]\{36\}\.jpg"```
