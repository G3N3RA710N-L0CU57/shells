# Upgrade a shell  

`python -c 'import pty;pty.spawn("/bin/bash")'`  

Background shell.

`CTRL+Z`  

`stty raw -echo`  

`fg`  

Hit enter twice.  

Open another terminal window.

`echo $TERM`  

`stty size`  

In reverse shell, enter results from above.  

```
export TERM=xterm-256colour
stty rows 67 columns 318
```  

