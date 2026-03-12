# 📊 Individual Progress Scorecard

## Daily Training Log

**Date:** _______________ | **Training Day:** ___/180 (or ___/90 for 3-month plan)

### 1. Time Investment

- [ ] Training time today: _______ hours
- [ ] Goal met? (Yes/No)
- [ ] Consistency streak: _____ days

**Points:**

- 2+ hours = 10 points
- 1-2 hours = 5 points
- <1 hour = 2 points
- Missed day = 0 points (streak resets)

### 2. Challenge Completion

| Difficulty      | Challenges Solved | Points Earned |
| --------------- | ----------------- | ------------- |
| Easy            | _____ × 5 pts     | _____         |
| Medium          | _____ × 15 pts    | _____         |
| Hard            | _____ × 30 pts    | _____         |
| Expert          | _____ × 50 pts    | _____         |
| **Daily Total** |                   | **_____**     |

### 3. Quality Indicators

- [ ] Created writeup for at least 1 challenge (+10 pts)
- [ ] Reviewed 3+ writeups from others (+5 pts)
- [ ] Learned new technique/tool (+10 pts)
- [ ] Updated cheat sheet (+5 pts)
- [ ] Practiced timed challenge (+5 pts)

**Quality Points Total:** _____

### 4. Category Focus Today

Which categories did you practice?

- [ ] Web Exploitation
- [ ] Binary Exploitation / Pwn
- [ ] Cryptography
- [ ] Reverse Engineering
- [ ] Forensics
- [ ] OSINT
- [ ] Other: ___________

**Primary Specialty:** _____ minutes

**Secondary Specialty:** _____ minutes

**Other Categories:** _____ minutes

### 5. Reflection (Qualitative)

**What went well today?**

Disko 1 challenge wants me to find the flag in the disk image. First, I copied the file link and used "wget <link here>" to download it. Unfortunately it was in gz file so I need to decompress it using "gunzip <name of the file>". The hints says that strings may help so I run "strings <file name> | grep pico" to search for words with "pico" on it. Finally I got the flag. 

"RED", the second challenge give me a color red picture. It seems pure but it wasn't. The flag must be hidden in the picture. First, I copied the file link and download it, looked for clue by running "strings <file name>" and a poem came out. What is odd is the first letter of each line had a message saying "check LSB", a steganography stuff. So I used cyberchef and upload the file I downloaded in my local computer. I extract the LSB and used the pattern "RGBA" since the hint says "Red?Ged?Bed?Aed?". I got data but in base64 so I converted it from base64 and got the flag.

Third challenge is called "PH4nt0m 1ntrud3r". There is a need to download wireshark app to access pcap file and it took a while to be downloaded. It was a challenge because you have to check every packets and convert its payload data from base to complete the flag. I found all the fragments and got the flag.

Fourth challenges is called "Verify". I am back to using webshell and I encountered another command tools. I don't have any idea so I rely on yt tutorials once again. The challenge needs me to use another directories in the webshell and honestly I struggled more than the previous challenge I solved since there a few instructions you need to follow. At the end I identified the file and got the flag.

**What challenged you?**



**Key learning:**

---

**Tomorrow's focus:**

---
