Brute-Force Attack, Cryptanalysis, and One-Time Pad

Q1 - True or False: Brute-force attack assumes that the attacker can distinguish between the correct and the incorrect key after the decryption trial. For example, the incorrect key can yield gibberish while the correct key yields a meaningful message.

True

Q2 - When the key is 10-bits long, how many decryptions do the brute-force attacker try in the worst case (this is the worst case in the Alice-Bob perspective and corresponds to the case when the attacker gets lucky)?

1 (when gets lucky is always 1!)

Q3 - When the key is 10-bits long, how many decryptions do the brute-force attacker try on average?

2^(n-1) = 2^(9) = 512


Q4 - When the key is 64-bits long, how long does it take in days for an attacker to brute-force search/attack for the key on average? The attacker can perform 10 trillion (10^13) decryptions per second, given the attacker processor and the encryption/decryption algorithm. 

n - 1 = 63
2^(n-1)/ (10^13) / 3600 / 24 = 10.67 days

Q5 - True or False: Known-plaintext attack is a stronger threat than ciphertext-only attack because the attacker uses the known plaintext-ciphertext pairs to more efficiently find the key that is being used by Alice and Bob.

True

Q6 - Is the following claim (that your friend generated a true one-time pad for perfect secrecy) true or false? 

A friend wants to use a one-time pad to encrypt a data of size 1 kilobyte/KB and ensure perfect secrecy. He generates a key that is of size 1KB by taking an 1B-long seed and using a deterministic algorithm to produce a 1KB-long key. The friend uses a secret algorithm, which he does not tell anybody, and the output key passes the pseudo-random test published by US NIST.

False


Q7 - True or False: One-time pad is popularly used for systems that require secure data protection.

False. 
