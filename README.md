# AES-implementation
A simple password-based AES encryption (AES-256-GCM symmetric encryption construction) with message authentication.

AES-GCM example in Python generates a random encryption key (secret key) and uses it to encrypt a text message, then decrypts it back to the original plaintext message

istall AES pythonlibtrary through
 
    pip install pycryptodome  
    
The AES-GCM encryption takes as input a message + encryption key and produces as output a set of values: { ciphertext + nonce + authTag }.
    The ciphertext is the encrypted message.
    
    The nonce is the randomly generated initial vector (IV) for the GCM construction.
    
    The authTag is the message authentication code (MAC) calculated during the encryption.

The encryption key size generated in the above code is 256 bits (32 bytes) and it configures the AES-GCM cipher as AES-256-GCM.
