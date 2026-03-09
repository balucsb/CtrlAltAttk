# 📊 Individual Progress Scorecard

## Daily Training Log

**Date:** 03/09/26 | **Training Day:** 3/90 
### 1. Time Investment

- [ ] Training time today: 1 hour and 20 min
- [x] Goal met? (Yes/No)
- [ ] Consistency streak: 1 day

**Points:**

- 2+ hours = 10 points
- 1-2 hours = 5 points
- <1 hour = 2 points
- Missed day = 0 points (streak resets)

### 2. Challenge Completion

| Difficulty      | Challenges Solved | Points Earned |
| --------------- | ----------------- | ------------- |
| Easy            |     1 × 5 pts     |     5         |
| Medium          | _____ × 15 pts    | _____         |
| Hard            | _____ × 30 pts    | _____         |
| Expert          | _____ × 50 pts    | _____         |
| **Daily Total** |                   | **5**     |

### 3. Quality Indicators

- [X] Created writeup for at least 1 challenge (+10 pts)
- [ ] Reviewed 3+ writeups from others (+5 pts)
- [x] Learned new technique/tool (+10 pts)
- [x] Updated cheat sheet (+5 pts)
- [ ] Practiced timed challenge (+5 pts)

**Quality Points Total:** 25

### 4. Category Focus Today

Which categories did you practice?

- [ ] Web Exploitation
- [ ] Binary Exploitation / Pwn
- [ ] Cryptography
- [ ] Reverse Engineering
- [x] Forensics
- [ ] OSINT
- [ ] Other: ___________

**Primary Specialty:** 90 minutes

**Secondary Specialty:** _____ minutes

**Other Categories:** _____ minutes

### 5. Reflection (Qualitative)

**What went well today?**

I successfully solved the Flag in Flame forensics challenge and obtained the flag. First, I copied the file link, opened the webshell, and download the file using the command line “wget <file link here>”. I run ‘cat logs.txt’ to read the contents of the logs.txt file. I converted the data into base64 using “cat logs.txt | base64”.  I, then, run ‘’ cat logs.txt | base64 -d >> logs.png” which extracts a Base64-encoded image hidden inside a text file and converts it back into a viewable image file. I found a string data like in a hexcode format. So I copied it and use cyberchef website that can decode it. Finally, I got the ctf flag.

**What challenged you?**

I already know the first thing I should do but I still have to rely on tutorials after. Whenever I encounter new commands, I tried to search for its function and understand it.

**Key learning:**

I used a new set of commands for converting the data into base64 and decode it back to its original binary format, then converts it back into a viewable image file.

**Tomorrow's focus:**

Complete the next challenges.
