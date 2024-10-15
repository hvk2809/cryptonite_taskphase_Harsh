# Pondering PATH
## The Path Variable
- Process: set the PATH="" which will remove all the commmands and then execute the file
- Flag: pwn.college{UZrQ94-l78-BLZZciw1J61S_iLU.dZzNwUDLzUjN0czW}
## Setting PATH
- Process: set the PATH=/challenge/more_commands/ and then run /challenge/run
- Flag: pwn.college{41YrzE5zTtEWtY5YZtqIQQca6D4.dVzNyUDLzUjN0czW}
## Adding Commands
- Process: first find cat command directory using find / -name cat and then create win and inside the file write "usr/bin/cat /flag" and make it a executable file using chmod. After this change the PATH to /home/hacker and then run /challenge/run
- Flag: pwn.college{o0x2AReUUdAtRyQVoPhwe2-7lts.dZzNyUDLzUjN0czW}
## Hijacking Commands
- Process: we will create our own rm executable command which will read /flag so to access cat we will find path of cat and then write the rm file in /home/hacker to read flag. After this will make rm a executable file and then set the PATH to /home/hacker. If we then run /challenge/run we will get the flag.
- Flag: pwn.college{8hC-DfsDSvENh9_npPBWFf38gIn.ddzNyUDLzUjN0czW}
