
# Blowfish Algorithm

Blowfish is an encryption technique designed by Bruce Schneier in 1993 as an alternative to
DES Encryption Technique. It is significantly faster than DES and provides a good
encryption rate with no effective cryptanalysis technique found to date. It is one of the first,
secure block ciphers not subject to any patents and hence freely available for anyone to use.
1. blockSize: 64-bits
2. keySize: 32-bits to 448-bits variable size
3. number of subkeys: 18 [P-array]
4. number of rounds: 16
5. number of substitution boxes: 4 [each having 512 entries of 32-bits each]


# Advantages and Disadvantages of Blowfish Algorithm:

● Blowfish is a fast block cipher except when changing keys. Each new key requires
a pre-processing equivalent to 4KB of text.

● It is faster and much better than DES Encryption.

● Blowfish uses a 64-bit block size which makes it vulnerable to birthday attacks.

● A reduced round variant of blowfish is known to be susceptible to known
plaintext attacks(2nd order differential attacks – 4 rounds).

# Applications of Blowfish Algorithm:

● Bulk Encryption.

● Packet Encryption(ATM Packets)

● Password Hashing

![alt text](https://media.geeksforgeeks.org/wp-content/uploads/20190929214411/encryption-blowfish.jpg)

