# Comprehending Commands Linux Luminarium
## Cat: not the pet but command
- Process: use the command 'cat' and argument flag to access flag
- Flag: pwn.college{IvewDo83jvLu-N3pT1Pmpbbbg6L.dFzN1QDLzUjN0czW}
## catting absolute paths
- Process: use the command 'cat' and argument as absolute path "/flag"
- Flag: pwn.college{cCviUub_qMofXcytV2OzRebhvMc.dlTM5QDLzUjN0czW
## More catting practice
- Process: Find the path of flag and pass the full path as argument to cat
- Flag: pwn.college{w8vZoK1-crTTue18o26MNo2y8wG.dBjM5QDLzUjN0czW}
## Greeping for a Needle in Haystack
- Process: search for string "pwn" using grep command in /challenge/data.txt file
- Flag: pwn.college{UKU1V5AUHGC6aamBGgHY1Dgimj1.ddTM4QDLzUjN0czW}
## Listing Files
- Process: list the items in /challenge using ls and then execute the changed name of run file to get the flag
- Flag: pwn.college{8ZQqGZPPxe8i61_DS5kxjFJ8Jq8.dhjM4QDLzUjN0czW}
## Touching Files
- Process: Create two files using touch command and then execute /challenge/run
- Flag: pwn.college{YjkJ6sMMKxpNRkDobRMITkfSnkT.dBzM4QDLzUjN0czW}
## Removing Files
- Process: Remove the "delete_me" file using rm command
- Flag: pwn.college{AdRMyoOvbLX7ooZDQm-Ylf-LyQb.dZTOwUDLzUjN0czW}
## Hidden Files
- Process: find the hidden file in / using -a after the command ls and then read the file using cat
- Flag: pwn.college{Y6CizsTklFYQHTBBqHKJxHWOXna.dBTN4QDLzUjN0czW}
## An Epic Filesystem Quest
- Process: Use the commmand cd,ls,ls -a,cat and follow the hints and clues to access the flag
- Flag: pwn.college{k9pB06rbnYgn3XxJbl0QMYszo_u.dljM4QDLzUjN0czW}
## Making Directories
- Process: Make a directory using mkdir and then create file inside it using touch named college
- Flag: pwn.college{8WYsr9D8MxsjDDxjB8e99Uf-R30.dFzM4QDLzUjN0czW}
## Finding Files:
- Process: use find / -name flag to find all flag directories and files and then use hit and trial to find the actual flag which was found in /opt/linux/linux-5.4/drivers/usb/gadget/function/flag
- Flag: pwn.college{AQSFWjnIlPbAf-Qj24lkjfcI9Dl.dJzM4QDLzUjN0czW}
## Linking Files
- Process: use command ln -sf /flag /home/hacker/not-the-flag. We use sf instead os cause -s cannot overwrite existing link which is a  broken link so -sf does that
- Flag: pwn.college{cc3tB2Znv4P_jVIYunm6qghMCXE.dlTM1UDLzUjN0czW}
