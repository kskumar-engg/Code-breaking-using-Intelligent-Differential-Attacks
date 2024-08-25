
# Project Title

Using differential cryptanalysis to break algorithms like Vignere cipher and playfair cipher, RSA.



## Deployment

To generate the keys and cipher texts, use Module 1.

Module 1: 

Select the encryption algorithm > Update to required key size > click generate key.

Add plain text and click on "Encrypt"


As we are working on differential attacks, make sure the key is not regenerated when different plain texts are used for same algorithm(apart for RSA).

RSA:

Here the same plain text has to be used and atleast 3 cipher texts should be generated. Generate a different key each time. Save the public key modulus value(n) in a file for each generated key. Use 'Save PK(n)' to save n to folder in a txt format.
Make sure the generated cipher texts and keys should have same order. i.e (eg:save 2nd cipher text and 2nd key with right names) so that while differential attack right key is associated for right cipher text.


Differential attacks:

Use module 2 for this. Select the cipher text and click attack.

For RSA, select the public key moduli(n) aswell and upload to perform the attack.


Note: Update the paths in the code to include the libraries

Needs installation of libraries like:
pycryptodome, gmpy2. Additional instructions to add other packages have been added in the code.
