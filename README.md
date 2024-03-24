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

# Compare
Salsa20 Generation Time: 5.387058973312378 seconds
RC4 Generation Time: 0.0003523826599121094 seconds
