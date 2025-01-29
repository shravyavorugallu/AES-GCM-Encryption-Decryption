# AES-GCM-Encryption-Decryption
# AES-GCM Encryption and Decryption in Python

## Description
This Python script demonstrates the use of **AES (Advanced Encryption Standard) in GCM (Galois/Counter Mode)** for encrypting and decrypting English text. AES-GCM provides both **confidentiality** and **integrity**, making it a widely used encryption mode for secure communication.

The script:
- Encrypts a given plaintext message using a randomly generated AES key.
- Decrypts the ciphertext back to its original plaintext.
- Ensures data integrity using an authentication tag.

## Features
- **AES-128 encryption** using a **random 16-byte key**.
- **GCM mode** for authenticated encryption.
- **Nonce-based encryption** to prevent replay attacks.
- **Data integrity check** using an authentication tag.

## Prerequisites
- Python 3.x installed.
- `pycryptodome` library installed.

## Installation
Install the required library using pip:
```sh
pip install pycryptodome
```
## Usage
Run the script to see encryption and decryption in action:
``` sh
python aes_gcm.py
```

## Code Overview
The script consists of:

- encrypt(plaintext, key): Encrypts a string using AES-GCM.
- decrypt(nonce, ciphertext, tag, key): Decrypts and verifies integrity.
- Example usage section to demonstrate encryption and decryption.

## Acknowledgments
Used PyCryptodome's documentation for AES-GCM implementation.

Followed general cryptographic best practices for secure encryption.

## License
This project is licensed under the MIT License.
