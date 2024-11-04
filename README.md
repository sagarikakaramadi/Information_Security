# Information_Security
This repository demonstrates a secure message encryption and decryption system using Elliptic Curve Cryptography (ECC) for key exchange and AES-GCM for encryption. The implementation enables secure, end-to-end encrypted communication, allowing two parties to securely exchange a secret key and encrypt/decrypt messages.

**Features**
**ECC Key Generation**: Creates ECC key pairs for secure communication.
**ECDH Key Exchange**: Uses Elliptic Curve Diffie-Hellman to derive a shared secret key between two parties.
**AES-GCM Encryption**: Encrypts messages using the shared key with AES-GCM, which provides confidentiality and integrity.
**AES-GCM Decryption**: Verifies and decrypts messages encrypted by the other party.

**Dependencies**
To run this code, you’ll need:
1. Python 3.6+
2. cryptography library
Install the required dependencies with:
  --- pip install cryptography
