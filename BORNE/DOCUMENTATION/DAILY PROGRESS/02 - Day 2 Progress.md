# 📊 Individual Progress Scorecard

## Daily Training Log

**Date:** Feb. 12, 2026 | **Training Day:** 2/90 for 3-month plan

### 1. Time Investment

- [ ] Training time today: 1 hours
- [ ] Goal met? (Yes/No)
- [ ] Consistency streak: 2 days

**Points:**

- 2+ hours = 10 points
- 1-2 hours = 5 points
- <1 hour = 2 points
- Missed day = 0 points (streak resets)

### 2. Challenge Completion

| Difficulty      | Challenges Solved | Points Earned |
| --------------- | ----------------- | ------------- |
| Easy            |   1   × 5 pts     |      5        |
| Medium          | _____ × 15 pts    | _____         |
| Hard            | _____ × 30 pts    | _____         |
| Expert          | _____ × 50 pts    | _____         |
| **Daily Total** |                   | **5**     |

### 3. Quality Indicators

- [x] Created writeup for at least 1 challenge (+10 pts)
- [ ] Reviewed 3+ writeups from others (+5 pts)
- [x] Learned new technique/tool (+10 pts)
- [ ] Updated cheat sheet (+5 pts)
- [ ] Practiced timed challenge (+5 pts)

**Quality Points Total:** 20

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
I   successfully solved the Hidden in Plainsight forensics challenge and retrieved the flag. -Started with metadata analysis since it was hinted and switched strategies when metadata alone didn’t work. I used several forensic tools and commands: wget, ls, strings, exiftool, CyberChef for decoding Base64, and steghide to extract hidden files from the image.

---

**What challenged you?**
The initial approach using a metadata checker didn’t immediately give the flag. I needed to rely on tutorials to understand the webshell and next steps. Decoding multiple layers (Base64 → hidden password → steganography extraction) added complexity. Knowing which commands to try first (strings, exiftool, steghide) was not obvious at the start.

---

**Key learning:**
Not all forensic challenges are solved by metadata alone — sometimes clues lead to steganography. Suspicious metadata comments can indicate hidden data. Base64 encoding may appear multiple times and requires repeated decoding. Steghide is useful for extracting hidden content from images.
---

**Tomorrow's focus:**

--- 
