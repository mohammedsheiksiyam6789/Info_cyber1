# Encryption Techniques
## Learning objectives
- Understand cryptography basics
- Differciate between symmetric and asymmetric encrypytion
- Learn hashing and digital signature concepts

# Cryptography 
Cryptography is a technique of securing information and communication using codes to ensure confidentiality,integrity and authentication.

## Symmetric Encryption
- Uses one key for both encryption and decryption
- Fast, suitable for bulk data encryption

## Asymmetric Encryption 
- Uses two keys: Public key (for encryption ) & Private key (for decryption )
- Used for secure key exchance and digital communication

## Hashing 
- Coverts data into a fixed-length string.
- One-way process - cannot be reversed.
- Used for password storage and integrity checking.
- Common algorithm: SHA-256, MD5(Message Digest 5) (deprecated)

## Digital signature and certificates
- Ensure Authenticity  and non-repudiation.
- A digital signature uses private key to sign data and public key to verify.
- Certificates (X.509) are issued by certificate Authorities (CAs) for trust verification in HTTPs.

## Example
When visiting https://shashank.com
- browser verifies certificate signed by CA to ensure authenticity.
