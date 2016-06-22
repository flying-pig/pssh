pssh
====
fork form http://code.google.com/p/parallel-ssh/

add sudo mode, use sudo to run ssh

add option: -s, --sudo

> $ prsync -s -r -h hosts.txt /path/to/file /remote/path/to/file
>
> $ pssh -s -h hosts.txt command
