# File Globbing
## Match with *
- Process: pass the argument /ch* to cd which change the directory to /challenge and then execute /challenge/run
- Flag: pwn.college{IyJZfbu6zTucv9Gp-qVC92rH6Mf.dFjM4QDLzUjN0czW}
## Matching with ?
- Process: pass the argument /?ha??enge to cd and then execute /challenge/run
- Flag: pwn.college{AvbSOUENqp31FmWQjNVoUnzeRl8.dJjM4QDLzUjN0czW}
## Matching with []
- Process: change directory to /challenge/files and then execute /challenge/run file_[bash]
- Flag: pwn.college{cgeA55SSRfdENWxxRp-xn7PyPvs.dNjM4QDLzUjN0czW}
## Matching path with []
- Process: execute /challenge/run followed by absolute path of files
- Flag: pwn.college{0WHyiCWQw5oVOUw1N7aw3u1wF95.dRjM4QDLzUjN0czW}
## Mixing Globs
- Process: execute the line [cep]*
- Flag: pwn.college{wtgMUaM9o43aPY1rhDrQBGS3OqP.dVjM4QDLzUjN0czW}
## Exclusionary Globbing
- Process: Execute the line /challenge/run [!pwn]*
- Process: pwn.college{k8TJhRLwoFx0jR0bBtu3GQB38eA.dZjM4QDLzUjN0czW}
