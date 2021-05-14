# input, output error stream

* Reference: https://linuxroutes.com/what-is-linux-standard-input-output-error-and-how-to-redirect-stdout-and-stderr-to-file-in-linux/

## input

```cat 0< hello.txt```

## output

```df -h > /tmp/output.log```

## error

```df -t 2> /tmp/error.log```

## combination - output, error

Given situation: ".uxtecho " does not exits.
<br>
```ls . .uxtecho &> /tmp/stdall.log```
<br>
```ls . .uxtecho > /tmp/stdall2.log 2>&1```
