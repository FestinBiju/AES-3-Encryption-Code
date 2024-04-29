# AES Encryption and Decryption

This repository contains a Python script for performing encryption and decryption using the AES (Advanced Encryption Standard) algorithm with a 256-bit key. The script provides a simple command-line interface for encrypting and decrypting text.

## Features

- Encryption and decryption of text using AES with ECB mode.
- Generation of a random 256-bit key for encryption.
- History feature to track encryption and decryption operations.
- Simple command-line menu for user interaction.

## Requirements

- Python 3.x
- cryptography library

You can install the required library using pip:

pip install cryptography


## Usage

1. Clone this repository to your local machine:


git clone <https://github.com/FestinBiju/AES-3-Encryption-Code>


2. Navigate to the directory containing the script:

cd aes-encryption-decryption


3. Run the script:

python aes_encrypt_decrypt.py


4. Follow the on-screen menu to perform encryption or decryption:

   - Option 1: Encrypt (AES-3) - Enter text to encrypt.
   - Option 2: Decrypt (AES-3) - Enter the hexadecimal representation of the encrypted text.
   - Option 3: Show History - Display the history of encryption and decryption operations.
   - Option 4: Exit - Terminate the program.

## Note

- It's recommended to handle the generated key securely, as it is crucial for both encryption and decryption. Storing the key securely is essential for the security of your encrypted data.
- The script uses ECB mode for simplicity. However, ECB mode is not recommended for secure encryption of large data due to its vulnerability to certain attacks. For better security, consider using other modes like CBC or GCM.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
