# DES-Encryption
The Data Encryption Standard (DES) is a symmetric-key block cipher published by the National Institute of Standards and Technology (NIST).

DES is an implementation of a Feistel Cipher. It uses 16 round Feistel structure. The block size is 64-bit. Though, key length is 64-bit, DES has an effective key length of 56 bits, since 8 of the 64 bits of the key are not used by the encryption algorithm (function as check bits only).

FILE 1:
  decryption.py 
    It take 2 input : (1) Key of length 16 and can contains Hexa values(0-F) (2) A text which is to be decrypted and it should contain only Hexa values(0-F).
    
FILE 2:
  des.py
    It take 2 input : (1) Key of length 16 and can contains Hexa values(0-F) (2) A text which is to be encrypted and it should contain only Hexa values(0-F).
