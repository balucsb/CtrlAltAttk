# 📊 Individual Progress Scorecard

## Daily Training Log

**Date:** 3/12/26| **Training Day:** 5/90 

### 1. Time Investment

- [ ] Training time today: 3.5 hours
- [X] Goal met? (Yes/No)
- [ ] Consistency streak: 4 days

**Points:**

- 2+ hours = 10 points
- 1-2 hours = 5 points
- <1 hour = 2 points
- Missed day = 0 points (streak resets)

### 2. Challenge Completion

| Difficulty      | Challenges Solved | Points Earned |
| --------------- | ----------------- | ------------- |
| Easy            |     4 × 5 pts     | 20            |
| Medium          | _____ × 15 pts    | _____         |
| Hard            | _____ × 30 pts    | _____         |
| Expert          | _____ × 50 pts    | _____         |
| **Daily Total** |                   | **_____**     |

### 3. Quality Indicators

- [X] Created writeup for at least 1 challenge (+10 pts)
- [ ] Reviewed 3+ writeups from others (+5 pts)
- [X] Learned new technique/tool (+10 pts)
- [X] Updated cheat sheet (+5 pts)
- [X] Practiced timed challenge (+5 pts)

**Quality Points Total:** 30

### 4. Category Focus Today

Which categories did you practice?

- [ ] Web Exploitation
- [ ] Binary Exploitation / Pwn
- [ ] Cryptography
- [ ] Reverse Engineering
- [X] Forensics
- [ ] OSINT
- [ ] Other: ___________

**Primary Specialty:** 210 minutes

**Secondary Specialty:** _____ minutes

**Other Categories:** _____ minutes

### 5. Reflection (Qualitative)

**What went well today?**

Disko 1 challenge wants me to find the flag in the disk image. First, I copied the file link and used "wget <link here>" to download it. Unfortunately it was in gz file so I need to decompress it using "gunzip <name of the file>". The hints says that strings may help so I run "strings <file name> | grep pico" to search for words with "pico" on it. Finally I got the flag. 

"RED", the second challenge give me a color red picture. It seems pure but it wasn't. The flag must be hidden in the picture. First, I copied the file link and download it, looked for clue by running "strings <file name>" and a poem came out. What is odd is the first letter of each line had a message saying "check LSB", a steganography stuff. So I used cyberchef and upload the file I downloaded in my local computer. I extract the LSB and used the pattern "RGBA" since the hint says "Red?Ged?Bed?Aed?". I got data but in base64 so I converted it from base64 and got the flag.

Third challenge is called "PH4nt0m 1ntrud3r". There is a need to download wireshark app to access pcap file and it took a while to be downloaded. It was a challenge because you have to check every packets and convert its payload data from base to complete the flag. I found all the fragments and got the flag.

Fourth challenges is called "Verify". I am back to using webshell and I encountered another command tools. I don't have any idea so I rely on yt tutorials once again. The challenge needs me to use another directories in the webshell and honestly I struggled more than the previous challenge I solved since there a few instructions you need to follow. At the end I identified the file and got the flag.

**What challenged you?**
I solved 4 challenges today and it was fun but it was challenging to me everytime I encounter new set of commands and third party tool to use since it was my first time encountering it.



**Key learning:**

Disko 1: I learned how to handle compressed forensic files by downloading them with wget, decompressing them using gunzip, and using the strings command with grep to quickly locate hidden text such as flags inside disk images.

RED: This challenge taught me that images can hide information through steganography. By analyzing clues in the file using strings, identifying hints about LSB (Least Significant Bit) encoding, and using tools like CyberChef, I was able to extract hidden data and decode it from Base64.

PH4nt0m 1ntrud3r: I learned how network forensic analysis works by examining packet capture files using Wireshark. By inspecting packet payloads and reconstructing fragmented data, I was able to recover pieces of the flag.

Verify: This challenge helped me practice navigating directories and using command-line tools in a webshell environment. It showed me the importance of carefully following instructions and exploring files within different directories to verify and locate the correct file containing the flag.

**Tomorrow's focus:**

--- complete other challenges
