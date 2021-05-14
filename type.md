# type

* Reference: 
  * https://linuxize.com/post/linux-type-command
  * https://www.howtoforge.com/linux-type-command
  * https://www.geeksforgeeks.org/type-command-in-linux-with-examples
  
```type wc``` input
<br>
```wc is /usr/bin/wc``` output

```type sleep head``` input
<br>
```sleep is /bin/sleep``` output
<br>
```head is /usr/bin/head```

## output: alias

given is an alias like ```ll``` which is ```ls -latr```.
<br>
```type -t ll```

## output: function

```type -t rvm```

## output: builtin

```type -t echo```

## output: file

```type -t cut```

## output: keyword

```type -t for```

## display path

Path is done by using the argument ```-P```.

```type ls``` input
<br>
ls is aliased to ```ls --color=auto``` output
<br><br>
```type -P ls``` input
<br>
```/bin/ls``` output
