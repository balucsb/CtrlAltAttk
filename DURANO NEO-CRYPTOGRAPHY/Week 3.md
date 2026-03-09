Activity 1: CryptoPals - "Set 1, Challenge 2"

- Wrote a function to take two equal-length hexadecimal strings and XOR them against each other.

- This solidified my understanding of XOR. I learned that in cryptography, if you XOR a message with a key to encrypt it, you just XOR the result with the exact same key to get the original message back.

Activity 2: CryptoPals - "Set 1, Challenge 3"

- Decrypted a message that was XOR'd against a single unknown character. I used a scoring metric based on English letter frequency to find the right key automatically.

- This was a massive lightbulb moment! Instead of guessing manually, I taught the computer what "normal English" looks like (lots of spaces, vowels, and common letters like 'T' and 'E'). The computer tested every possible key and handed me the most logical English sentence.

Activity 3: picoCTF - "New Caesar"

- Read a custom Python script that shifted characters based on a key, and wrote a reverse script to try all 16 possible keys to read the flag.

- "Rolling your own crypto" is a terrible idea. The creator of the challenge tried to make a new version of the Caesar cipher, but because the key space was so small (only 16 possibilities), a simple brute-force attack broke it in less than a second.

- Activity 5: CryptoHack - "Passwords as Keys"

- Decrypted a message encrypted with AES-ECB where the key was just a word taken from a dictionary file of common passwords. Even if you use AES (which is military-grade encryption), it is completely useless if your password is weak.
