# EX-NO-6-Pseudo-Random-Number

# AIM: 

Implementation of Pseudorandom Number Generation Using Standard library

# Algorithm:
Import the secrets module:

This module provides cryptographically secure random functions.
Generate a secure random integer:

Use secrets.randbelow(n) to get a random integer between 0 and n-1.
Generate a secure random number with a specific bit length:

Use secrets.randbits(bit_length) to generate a random number with a given number of bits.
Generate a secure random token (hexadecimal):

Use secrets.token_hex(nbytes) to generate a secure random token in hex format. The nbytes parameter specifies the number of bytes, and the result will be a string with twice that number of hex characters.
Display or use the generated random values:

Print or use the generated values for your cryptographic needs.

# Program
```
import secrets

random_int = secrets.randbelow(10)

random_bits = secrets.randbits(128)

random_token = secrets.token_hex(16)

print("EX-NO-6-Pseudo-Random-Number by Preethi M 212222100037")
print("Secure Random Integer (0 to 9):", random_int)
print("Secure 128-bit Random Number:", random_bits)
print("Secure Random Token (32 characters hex):", random_token)
```
# Output:
![image](https://github.com/user-attachments/assets/b87c188a-2165-4b6d-aa55-cc9fab558477)

# Result
Thus Pseudorandom Number Generation Using Standard library has been executed successfully.
