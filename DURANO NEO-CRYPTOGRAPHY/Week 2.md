
Activity 1: CryptoHack - "Greatest Common Divisor (GCD)"

- Wrote a simple script to find the largest number that divides two integers without a remainder using the Euclidean Algorithm.

- The Euclidean Algorithm is super fast, even with massive numbers, which is exactly why it's used in setting up public-key encryption.

Activity 2: CryptoHack - "Modular Arithmetic 1"

- Solved basic equations using modulo (%), which is essentially clock math (finding the remainder after division).

- I realized that almost all modern cryptography relies on modular arithmetic. It wraps numbers around in a circle, which makes it easy to calculate in one direction but extremely difficult to reverse-engineer.

Activity 3: picoCTF - Mind your Ps and Qs

- Given the values for $c$ (ciphertext), $n$ (modulus), and $e$ (public exponent), I had to decrypt an RSA message. $n$ was small enough that I could factor it into its prime numbers, $p$ and $q$.

- This was my first real RSA decryption! I learned that RSA's security entirely depends on $n$ being too large to factor. If an attacker can figure out the two prime numbers that multiply to make $n$, the whole system breaks immediately.

Activity 4: picoCTF asy1

- ecrypted a message using a Vigenère cipher and a provided table.

- The Vigenère cipher is like the Caesar cipher (ROT13), but instead of shifting by one fixed number, it shifts by a repeating keyword. It showed me how early cryptographers tried to defeat frequency analysis (where attackers guess letters based on how often they appear, like 'E').
