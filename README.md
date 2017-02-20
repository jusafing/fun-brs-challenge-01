## Detect AES in ECB mode


* Challenge Series BRS v2017.2.2
* Category: Scripting
* Level   : Basic
* Source  : https://cryptopals.com/sets/1/challenges/8

## Description
In this file are a bunch of hex-encoded ciphertexts.

One of them has been encrypted with ECB.

Detect it.

Remember that the problem with ECB is that it is stateless and deterministic; the same 16 byte plaintext block will always produce the same 16 byte ciphertext.