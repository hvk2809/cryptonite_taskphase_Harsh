# Perceiving Permissions
## Changing File Ownership
- Process: Change the owner of /flag to hacker using command chown and then read the file.
- Flag: pwn.college{YHqSSP4guRBOScbw11mI9XQpVDq.dFTM2QDLzUjN0czW}
## Groups and Files
- Process: Change the group to hacker for the file /flag using chgrp and then read the file.
- Flag: pwn.college{4ydomi5pYNmQo_71kbDStr5Li3m.dFzNyUDLzUjN0czW}
## Fun with Group Names
- Process: first use the id command to check which group the user belong to and then use chgrp command to /flag access to that group and then read it.
- Flag: pwn.college{UzYHzjZhFpgSrevGLvOYKwetgfh.dJzNyUDLzUjN0czW}
## Changing Permissions
- Process: change mode to other and give read access using chmod command
- Flag: pwn.college{gv_ypY_G-BU9jPKAw5yj29F3wTD.dNzNyUDLzUjN0czW}
## Executable Files
- Process: Change the access of execution of /challenge/run
- Flag: pwn.college{MCdRDi4uCPHcFJxz2E6ytsnEAg1.dJTM2QDLzUjN0czW}
## Permission Tweaking Practice
- Process: Change permissions accroding to the demands of the challenge
- Flag: pwn.college{8l3D32j6BVSFg1ppMqsRL7i8wNZ.dBTM2QDLzUjN0czW}
## Permissions Setting Practice
- Process: Change permissions accroding to the demands of the challenge using = and , .
- Flag: pwn.college{AujzOX-E3Nzhnywj2kvAsX6L4Gx.dNTM5QDLzUjN0czW}
## The SUID Bit
- Process: Execute the file /challenge/getroot as root for that set the file as SUID bit usind the command chmod u+s /challenge/getroot
- Flag: pwn.college{ghXedMKbIffh_SYlMV5bbN7yqHE.dNTM2QDLzUjN0czW}
