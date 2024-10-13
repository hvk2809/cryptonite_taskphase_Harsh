# OASIS CTF Report

## Level 13-Microsoft StrongEdge
Though this level was not challenging, it was definitely interesting. Knowing the behaviour of .pptx files to be similar to a zip file, I opened the .pptx format file using a file archiver like WinRAR/7-zip. Found the image in the media folder and applied ROT-13 to it to arrive at the flag.

## Level 16- Nom-Nom
A level which can be considered decently challenging for a beginner. This level took my team around 40 minutes to solve. We were initially trying to mess with the css used to create the dots, but when I tried opening other tabs, I discovered the cookie called "admin" on the network tab, which also fit the requirement to play the pac-man game. On setting the value of the admin cookie to 'true' and refreshing the page, the pacman ate the dots and revealed the flag for the level. This was quite interesting, as this was the first time I had played with cookie values.

## Level 17-Quench your Thirst
Though this level seemed easy at first, it turned out to have more to it than what meets the eye. On deciphering the ciphertext by using the monoalphabetic substitution cipher bruteforce on dcode.fr, I had discovered the katbin link. However, the link did not seem to be working, and I even raised my first ticket here, asking the moderators if there was an error with the ciphertext. When they said that the endpoint was incorrect, I reviewed the 4 alphabets which kept changing on bruteforcing, and then realised that these alphabets were being used for the first time in the entire cipher text. Now, it was a simple task of changing the endpoint of the link by rearranging those 4 alphabets. This would have taken a simple script, or a bruteforce. There were a total of 24 possible ways to arrange the letters. Fortunately, while my teammate tried writing a code, I got it correctly on my 3rd attempt while manually bruteforcing.

## Level 20-Firewall Jail
This level was solved by my teammates when I was away. It seems like an interesting challenge, as they had to set the userid url parameter to -1.

## Level 21-Heads up, Tails down
This level was rather straight forward, but still interesting, as it required us to open a hexeditor, and repair the file by fixing it with the png file signature, which can be searched online or by opening a normal png file on the hexeditor.

## Level 22-Press Start
A level which drained the will to live out of my teammates and myself. It was a rather simple challenge, but we had no clue how to go about it. After several hours of learning and asking mods for guidance, the hint confirmed that what we had initially tried doing was the correct path, but it did not seem to work. Then, I learnt that User-Agent had to be tested by changing the header to just "OASISPlayer". Then, while trying to solve it on the browser using MODHeader, I realised our approach was incorrect as simply appending ?name=Cryptonite was not solving it. This led me back to the hours we spent analysing the code, where we were constantly trying to understand the significance of the POST method used in the function call. Following this, all it took was 5 minutes to solve the level using a simple curl command on the system command prompt.
curl -X POST -H "User-Agent: OASISPlayer" "https://startgame.oasis.cryptonite.live/givemetheFlag?name=cryptonite&rank=4"
{"Flag":"OASIS{G37_d035_n07_4lw4y5_G37_th1ng5}"}

Overall, it was a fun experience, and developed further interest in CTFs. It showed that there is much left to learn, and I hope that the Cryptonite student project will provide me with ample opportunities to learn and develop.
