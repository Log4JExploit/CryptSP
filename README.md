# CryptLib
Encryption and hashing library for Java
Provides helper classes for a few widely used algorithms

# Supported Algorithms
- AES (AES/GCM/NoPadding), key sizes: [128, 192, 256]
- RSA (RSA/ECB/OAEPWITHSHA-256ANDMGF1PADDING), key sizes: [1024, 2048, 4096]
- SHA1, key sizes: [160]
- SHA2, key sizes: [224, 256, 384, 512]
- SHA3, key sizes: [224, 256, 384, 512]

# Notes
This library can only work, if the desired algorithm is implemented by at least one provider in the jvm!
Note that the key size of '1' in the SHA2 implementation does NOT refer to an output bit length of 1, but rather