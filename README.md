# cryptonite_taskphase_Harsh
## Hello Hackers
### Intro to Commands
- Process: Command hello
- Flag: pwn.college{461Yg2PcWGDhBFQWcPzbBAVIyyd.ddjNyUDLzUjN0czW}
### Intro to Arguments
- Process: Command hello and pass argument Hackers
- Flag: pwn.college{4IE1L5izxe_nZjZeo3dWqNdqNT9.dhjNyUDLzUjN0czW}
## Pondering Paths
### The Root
- Process: to open a directory write its path example /cryptonite_taskphase_Harsh/filename
- Flag: pwn.college{AkVkYMYPH-ckL8eWoe26wnMVRk6.dhzN5QDLzUjN0czW}
### Program and Absolute Paths
- Process: to open a directory write its path example cryptonite_taskphase_Harsh/filename
- Flag: pwn.college{Y1bzOx4RWnLoCQzikzXth1K1V-z.dVDN1QDLzUjN0czW}
### Position thy self
- Process: use cd(change directory) which changes the current directory
- Flag: pwn.college{Isnl6zkM0JhyBZcQhBUvUzgjnpv.dZDN1QDLzUjN0czW}
### Position elsewhere
- Process: use cd(change directory) which changes the current directory
- Flag: pwn.college{4j9iW_brtTBXasppjbUhc_wycNc.ddDN1QDLzUjN0czW}
### Position yet Elsewhere
- Process: enter /challenge/run it will give you error and the actuat path then use that path to access flag
- Flag: pwn.college{cQQI_Fk_0qupwL-5X3GdL7wnri-.dhDN1QDLzUjN0czW}
### Implicit Relative Paths, from /
- Process: go to / directory and execute /challenge/run
- Flag: pwn.college{QDr7UaYGHjBePh6d2BtiyIzKgih.dlDN1QDLzUjN0czW}
### Explicit Relative Paths, from/
- Process: Go to / directory anf from there use that directory itself to go to /challenge/run
- Flag: pwn.college{0rDQZmFaUN4rSabBH06G4crZh9Y.dBTN1QDLzUjN0czW}
### Implicit Relative Paths
- Process: Use . to execute /challenge/run from the current directory
- Flag: pwn.college{cHS0cr3l1B-wGMXuKNIIDeLhhCi.dFTN1QDLzUjN0czW}
### Home Sweet Home
- Process: Use ~ this to access the path of current directory and pass an argument like "~/x" to /challenge/run
- Flag: pwn.college{wcjHC9fQjavNd_OO8LpR39TGzhe.dNzM4QDLzUjN0czW}
## Comprehending Commands Linux Luminarium
### Cat: not the pet but command
- Process: use the command 'cat' and argument flag to access flag
- Flag: pwn.college{IvewDo83jvLu-N3pT1Pmpbbbg6L.dFzN1QDLzUjN0czW}
### catting absolute paths
- Process: use the command 'cat' and argument as absolute path "/flag"
- Flag: pwn.college{cCviUub_qMofXcytV2OzRebhvMc.dlTM5QDLzUjN0czW
### More catting practice
- Process: Find the path of flag and pass the full path as argument to cat
- Flag: pwn.college{w8vZoK1-crTTue18o26MNo2y8wG.dBjM5QDLzUjN0czW}
### Greeping for a Needle in Haystack
- Process: search for string "pwn" using grep command in /challenge/data.txt file
- Flag: pwn.college{UKU1V5AUHGC6aamBGgHY1Dgimj1.ddTM4QDLzUjN0czW}
### Listing Files
- Process: list the items in /challenge using ls and then execute the changed name of run file to get the flag
- Flag: pwn.college{8ZQqGZPPxe8i61_DS5kxjFJ8Jq8.dhjM4QDLzUjN0czW}
### Touching Files
- Process: Create two files using touch command and then execute /challenge/run
- Flag: pwn.college{YjkJ6sMMKxpNRkDobRMITkfSnkT.dBzM4QDLzUjN0czW}
### Removing Files
- Process: Remove the "delete_me" file using rm command
- Flag: pwn.college{AdRMyoOvbLX7ooZDQm-Ylf-LyQb.dZTOwUDLzUjN0czW}
### Hidden Files
- Process: find the hidden file in / using -a after the command ls and then read the file using cat
- Flag: pwn.college{Y6CizsTklFYQHTBBqHKJxHWOXna.dBTN4QDLzUjN0czW}
### An Epic Filesystem Quest
- Process: Use the commmand cd,ls,ls -a,cat and follow the hints and clues to access the flag
- Flag: pwn.college{k9pB06rbnYgn3XxJbl0QMYszo_u.dljM4QDLzUjN0czW}
### Making Directories
- Process: Make a directory using mkdir and then create file inside it using touch named college
- Flag: pwn.college{8WYsr9D8MxsjDDxjB8e99Uf-R30.dFzM4QDLzUjN0czW}
### Finding Files:
- Process: use find / -name flag to find all flag directories and files and then use hit and trial to find the actual flag which was found in /opt/linux/linux-5.4/drivers/usb/gadget/function/flag
- Flag: pwn.college{AQSFWjnIlPbAf-Qj24lkjfcI9Dl.dJzM4QDLzUjN0czW}
### Linking Files
- Process: use command ln -sf /flag /home/hacker/not-the-flag. We use sf instead os cause -s cannot overwrite existing link which is a  broken link so -sf does that
- Flag: pwn.college{cc3tB2Znv4P_jVIYunm6qghMCXE.dlTM1UDLzUjN0czW}
## Digesting Documentaion
### Learning from Documention
- Process: pass --giveflag as argument to /challenge/challenge
- Flag: pwn.college{wUWBPDyA_hPJ9pT5_opvVps_xj0.dRjM5QDLzUjN0czW}
### Learning Complex Usage
- Process: Pass the argumet /flag to argument --printfile as /flag is the place where all the hidden files are present
- Flag: pwn.college{kUSOLQm3fyJPooTN1sJ1tLdwAt3.dVjM5QDLzUjN0czW}
### Reading Manuals
- Process: read the entire manual below the exact argument is given to pass to /challenge/challenge to get flag
- Flag: pwn.college{Ax5EPygeEDDApvGYIrcEqRRM1FO.dRTM4QDLzUjN0czW}
### Searching Manuals
- Process: Search in the manual for flag word it will give you the argument
- Flag: pwn.college{c7m8rBWMjs6SobzcRvasoNiR0bc.dVTM4QDLzUjN0czW}
### Searching for Manuals
- Process: use the commend man -k challenge to find the keyword challenge in all all man files and then find flag argument
- Flag: pwn.college{gcfAR_heng0g82eFHE28YxtaqBu.dZTM4QDLzUjN0czW}
### Helpful Programs
- Process: first execute /challege/challenge --help it gives its all arguments then we pass -p argument to it get our secret number and then pass the argument --give-the-flag 486 to /challenge/challenge
- Flag: pwn.college{MAQF4rQe8-vgDdDRn6gcUzEvUP_.ddjM4QDLzUjN0czW}
### Help for Builtins
- Process: First pass challenge to help we see all its shells and over there 'secret' value is given use that to access flag
- Flag: pwn.college{0-yWdGU7dR3z0ZNZP4RCs9V9Xvo.dRTM5QDLzUjN0czW}
## File Globbing
### Match with *
- Process: pass the argument /ch* to cd which change the directory to /challenge and then execute /challenge/run
- Flag: pwn.college{IyJZfbu6zTucv9Gp-qVC92rH6Mf.dFjM4QDLzUjN0czW}
### Matching with ?
- Process: pass the argument /?ha??enge to cd and then execute /challenge/run
- Flag: pwn.college{AvbSOUENqp31FmWQjNVoUnzeRl8.dJjM4QDLzUjN0czW}
### Matching with []
- Process: change directory to /challenge/files and then execute /challenge/run file_[bash]
- Flag: pwn.college{cgeA55SSRfdENWxxRp-xn7PyPvs.dNjM4QDLzUjN0czW}
### Matching path with []
- Process: execute /challenge/run followed by absolute path of files
- Flag: pwn.college{0WHyiCWQw5oVOUw1N7aw3u1wF95.dRjM4QDLzUjN0czW}
### Mixing Globs
- Process: execute the line [cep]*
- Flag: pwn.college{wtgMUaM9o43aPY1rhDrQBGS3OqP.dVjM4QDLzUjN0czW}
### Exclusionary Globbing
- Process: Execute the line /challenge/run [!pwn]*
- Process: pwn.college{k8TJhRLwoFx0jR0bBtu3GQB38eA.dZjM4QDLzUjN0czW}
## Practicing Piping
### Redirecting Output
- Process: echo output PWN to file COLLEGE
- Flag: pwn.college{kcNZXB_c4sVMj13klNx5e8SVWiy.dRjN1QDLzUjN0czW}
### Redirecting more Output
- Process: /challenge/run > myflag and then cat myflag
- Flag: pwn.college{0sxCEAU4-AUgaka3RBmlN4ahh4P.dVjN1QDLzUjN0czW}
### Appending Output
- Process: Two times append /challenge/run to my-flag
- Flag: pwn.college{4YpWsv5FJYST4QVnrGYcHfZWVKI.ddDM5QDLzUjN0czW}
### Redirecting Errors
- Process: Redirect Errors to instructions and output to myflag and then cat myflag
- Flag: pwn.college{0bakp9Gs0LbNYkX7nYwyCZRjfhS.ddjN1QDLzUjN0czW}
### Redirecting Input
- Process: First echo the word College to PWN and then redirect it to /challenge/run
- Flag: pwn.college{Irc2Hv_F3jpK4xtzUYdWkMJDWF8.dBzN1QDLzUjN0czW}
### Grepping Stored Results
- Process: First direct the output of /challenge/run to tmp/data.txt and then grep the word pwn
- Flag: pwn.college{wZ8tBi77YTtzEYXLJj2ACN1dJhN.dhTM4QDLzUjN0czW}
### Greping Live Output
- Process: execute /challenge/run and grep pwn using pipe(|)
- Flag: pwn.college{Q3bFiD-yBOpy3U4qi79XZdAFswR.dlTM4QDLzUjN0czW}
### Greping Errors
- Process: first redirect standard error to standard output using 2>&1 and then grep pwn
- Flag: pwn.college{AmAkRzGzb8Ke1fJRBpkj-v8-vsr.dVDM5QDLzUjN0czW}
### Duplicating Piped Data with Tee
- Process: tee the copy of pwn to different file and then cat the file to get secret code and then execute both the command
- Flag: pwn.college{80y2Y8lMCa-F-PVY53PYHZeGiQ3.dFjM5QDLzUjN0czW}
### Writing to Multiple Commands
- Process: Duplicate the data to give input in two files using tee >()
- Flag: pwn.college{8KKzRGazMR6KGQTQxXxsZqUMyGo.dBDO0UDLzUjN0czW}
### Split-piping stderr and stdout
- Process: Send stderr to /challenge/the and stdout to /challenge/planet from /challenge/hack
- Flag: pwn.college{sfq9jbovLejTbSdOx8PxHU2Ykq-.dFDNwYDLzUjN0czW}
## Shell Variables
### Printing Variable
- Process: just echo the variable FLAG
- Flag: pwn.college{I6753Oi8UGYWbGVfV4gPeFDH8mt.ddTN1QDLzUjN0czW}
### Setting Variables
- Process: set the value of variable PWN as COLLEGE
- Flag: pwn.college{Y7EiVh4BozRtYclPeWgwaG6EXcR.dlTN1QDLzUjN0czW}
### Multi-Word Variables
- Process: Set the variable PWN as "COLLEGE YEAH"
- Flag: pwn.college{8EbGQEliH3vgkytG9k0SmBsasbC.dBjN1QDLzUjN0czW}
### Exporting Variables
- Process: Set the value of COLLEGE to PWN and then export the variable PWN setting its value COLLEGE and then run /challenge/run passing the variable PWN
- Flag: pwn.college{sTrpjY177bD8k1p7agQXAdNSxje.dJjN1QDLzUjN0czW}
### Printing Exported Variables
- Process: use env command to print all the exported variable set and grep the word FLAG
- Flag: pwn.college{Q3MHcTsvmMhmDMePTfIvvtKOVyP.dhTN1QDLzUjN0czW}
### Sorting Command Output
- Process: Store the output os /challenge/run to PWN and then read it
- Flag: pwn.college{cKo1F0qROhvghL8d5tug4s-SoNs.dVzN0UDLzUjN0czW}
### Reading Input
- Process: use read command to set COLLEGE as the value of PWN
- Flag: pwn.college{o39w5WlbkRYy57f__hT_JR-Zyn_.dhzN1QDLzUjN0czW}
### Reading Files
- Process: use read command to set the value of variable PWN as output of /challenge/run
- Flag: pwn.college{YG_-xTLob8u4hEHtfflCSFncAx0.dBjM4QDLzUjN0czW}
