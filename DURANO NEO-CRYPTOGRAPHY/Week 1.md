Activity 1: picoCTF - "Mod 26"

- Solved a basic substitution cipher challenge where the letters were shifted by 13 places (ROT13).

- I learned that ROT13 is perfectly symmetrical. The same algorithm used to encrypt the text is used to decrypt it. It’s a great reminder that "shifting" letters doesn't provide real security, just obfuscation.

Activity 2: picoCTF - "bases"

- Decoded a strange-looking string of text that ended in an equals sign (=).

-  I discovered this is Base64 encoding. It’s not actually "encryption" but a way to convert binary data into readable text for safe transmission over the internet. The = sign at the end is a dead giveaway, acting as padding.

Activity 3: CryptoHack - "ASCII"

- Converted a list of numbers into text using an ASCII table.

- Every character on a keyboard corresponds to a specific number in the computer's memory. Understanding ASCII is foundational because, in cryptography, everything eventually breaks down into numbers before math can be applied to it.
