# SC4010-Applied Cryptography Project

This project involves demonstrations of multiple potnetial attacks against RSA cryptography

The project will demonstrate the following attacks:
- Wiener Attack (Small Decryption Key)


# Wiener Attack (Small Decryption Key)
RSA is vulnerable to attacks if the decryption key being used is sufficiently small, as it can be tempting to use smaller d's for faster decryptions. Wiener's attack will succeed for d< 1/3(n^(1/4)). This is improved by Boneh and Durfee by requiring it to be less than n^0.292. Larger e's tend to mean small d's, although this is not always the case. 

# Common Modulus Attack
RSA is vulnerable to attacks if the same message is encrypted twice with the same modulus but a different public key. Sometimes such problem may happen in the internet.