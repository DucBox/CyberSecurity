# Salsa20 Algorithm
The Salsa20 algorithm is a symmetric stream cipher designed to provide high security and performance. It operates on variable-length input data and produces ciphertext of the same length as the plaintext.

# Example usage
key = b"this_is_a_32_byte_key_for_salsa!"

nonce = b"nonce123"

plaintext = b"Hello, Salsa20!"

# Encrypt the plaintext
encrypted = encrypt(plaintext, key, nonce)

# Decrypt the ciphertext
decrypted = decrypt(encrypted, key, nonce)

# Result
Encrypted: 0109fc750bc2b016264d845aedb744

Decrypted: Hello, Salsa20!

# Compare Salsa20 to RC4

Salsa20 Generation Time: 5.387058973312378 seconds
RC4 Generation Time: 0.0003523826599121094 seconds

# Compare DES to RC4
Case 1:
Time taken for DES encryption: 0.001227 seconds

Time taken for RC4 encryption: 0.000046 seconds
Case 2:
Time taken for DES encryption: 0.000088 seconds

Time taken for RC4 encryption: 0.000043 seconds
Case 3:
Time taken for DES encryption: 0.000096 seconds

Time taken for RC4 encryption: 0.000045 seconds
Case 4:
Time taken for DES encryption: 0.000054 seconds

Time taken for RC4 encryption: 0.000035 seconds

Binary Data:
Time taken for DES encryption: 0.000157 seconds

Time taken for RC4 encryption: 0.000043 seconds

Numeric Data:
Time taken for DES encryption: 0.000127 seconds

Time taken for RC4 encryption: 0.000034 seconds

Repeated Character:
Time taken for DES encryption: 0.000120 seconds

Time taken for RC4 encryption: 0.000036 seconds

Mixed Data:
Time taken for DES encryption: 0.000134 seconds

Time taken for RC4 encryption: 0.000036 seconds

# Source Code
[Code](https://colab.research.google.com/drive/148CgeQQzID6h9XUVg9Igz2wtqXeK6Hin#scrollTo=wnQ-cZVr-4pb)
https://colab.research.google.com/drive/148CgeQQzID6h9XUVg9Igz2wtqXeK6Hin#scrollTo=wnQ-cZVr-4pb

# Github
https://github.com/DucBox/CyberSecurity
