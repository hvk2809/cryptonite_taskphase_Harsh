# Bandit Level
## Level 0
- Process: Find readme using ls and then read using cat
- Password: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
## Level 1
- Process: cat the file using command cat ./-
- Password: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
## Level 2
- Process: cat the file as it has spaces using " "
- Password: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
## Level 3
- Process: change the directory to inhere and then search for hidden files using ls -a command then cat that hidden file
- Passord: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
## Level 4
- Process: first search for file which is human readable using the file command "file ./*" * makes it read through all the files and then you get file7 is the correct file. After this cat the file
- Password: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
## Level 5
- Process: I knew how to use find command but did not know how to serach file size so i read the manual page of it and found the size command. After learning about it I used the command find -size 1033c.
- Password: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
## Level 6
- Process: use the command "find / -user bandit7 -group bandit6 -size 33c" after this bunch of file pops through after manually looking at the files, i found the password file path.
- Password: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
## Level 7
- Process: used the command grep and search for the word millionth
- Password: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
## Level 8
- Process: use the command "sort data.txt | uniq -u". After reading the manual about uniq i learned about the suffix -u use.
- Password: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
## Level 9
- Process: use strings command to print all the strings of the text file.
- Password: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
## Level 10
- Process: Use the command base64 -d(learned from the manual) to decode the text
- Password: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
## Level 11
- Process: read the file and use online rot 13 to decipher it
- Password: 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
## Level 12
- Process:
In this we have to decompressed multiple times to get to the password. There are two types of compression which has been used gzip and bzip2. Firstly we will conver the hex dump to a binary file with command "xxd -r file_name new_file" over -r is used because it is a hex dump. After converting it to binary we will check the file type and according to the compresseion decompress it.

For gzip compression:
1. Rename the file - "mv file_name file_name.gz"
2. decompressed it - "gunzip file_name.gz"

For bzipw compression:
1. Rename the file - "mv file_name file_name.bz2
2. decompressed it - "bunzip2 file_name.bz2"
if it is converted to POSIX tar archive we need to extract using tar.
As tar was used to bundle the file together before compression so now we have to extract it.
"tar -xvf file_name"
-x : to extract
-v : shows details of extraction
-f : file to extract from
- Password: FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
