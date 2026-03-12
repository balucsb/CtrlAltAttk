# 📊 Individual Progress Scorecard

## Daily Training Log

**Date:** 03/11/2024| **Training Day:** 4/90 

### 1. Time Investment

- [ ] Training time today: 1 hour
- [x] Goal met? (Yes/No)
- [ ] Consistency streak: 3 days

**Points:**

- 2+ hours = 10 points
- 1-2 hours = 5 points
- <1 hour = 2 points
- Missed day = 0 points (streak resets)

### 2. Challenge Completion

| Difficulty      | Challenges Solved | Points Earned |
| --------------- | ----------------- | ------------- |
| Easy            |    2  × 5 pts     |    10         |
| Medium          | _____ × 15 pts    | _____         |
| Hard            | _____ × 30 pts    | _____         |
| Expert          | _____ × 50 pts    | _____         |
| **Daily Total** |                   | **10**     |

### 3. Quality Indicators

- [x] Created writeup for at least 1 challenge (+10 pts)
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

**Primary Specialty:** 60 minutes

**Secondary Specialty:** _____ minutes

**Other Categories:** _____ minutes

### 5. Reflection (Qualitative)

**What went well today?**

I successfully solve the CORRUPTED FILE challenge. First, I downloaded the file "file" to my local computer. I used "wget <filename>", "cat file", "hexdump file", "xxd file". I observed that the image seems broken. However the image header is different from that of a jpeg header so I used hexed.it website that let you modify the hex header of the file. I modify the file's header and match it with the jpeg header. I opened the file via browser I got to see the image containing the ctf flag.

**What challenged you?**
Using another command tools and third party tools are what challenge me. I did search and understand what they are and what they do.

**Key learning:**
Solving the corrupted file challenge in picoCTF helped me understand how digital evidence can still be recovered even when files appear damaged or unreadable. At first, the file seemed useless because it could not be opened normally, but by examining the file structure and using forensic tools, I learned that important data can still remain inside corrupted files.

**Tomorrow's focus:**

---Completer next challenges
