# Caesar Cipher Encryption and Decryption

This repository contains a Python script that implements the Caesar cipher algorithm, a classic method of encryption and decryption. The script allows users to input a message and a shift value, and it can either encrypt or decrypt the message using the Caesar cipher technique.

## Features

- **Encrypt a Message**: Shift each letter in the message by a specified number of places down the alphabet.
- **Decrypt a Message**: Reverse the encryption process to retrieve the original message.
- **Supports Uppercase and Lowercase**: Handles both uppercase and lowercase letters while leaving non-alphabetic characters unchanged.

## Installation

No additional libraries are required to run this script. It only requires Python 3.

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/ayisharizwi/prodigy_cs_01.git
   cd prodigy_cs_01
   ```

2. **Run the Script:**

   ```bash
   python caesarcipher.py
   ```

3. **Input Parameters:**

   The script will prompt you for the following input:

   - **Message**: The text you want to encrypt or decrypt.
   - **Shift Value**: The number of positions to shift each letter. This value should be an integer.

4. **Example:**

   ```bash
   Enter your message: Hello World
   Enter the shift value: 3
   ```

   The output will be:

   ```
   Encrypted Message: Khoor Zruog
   Decrypted Message: Hello World
   ```

## How It Works

1. **Caesar Cipher Algorithm:**
   - The Caesar cipher is a substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.
   - The shift value determines how far each letter is moved.
   - The script supports both encryption and decryption by reversing the shift during decryption.

2. **Encryption:**
   - The script shifts each letter in the message by the specified shift value.
   - Uppercase and lowercase letters are handled separately, preserving their case.
   - Non-alphabetic characters (e.g., spaces, punctuation) remain unchanged.

3. **Decryption:**
   - The decryption process simply shifts the letters in the opposite direction, reversing the encryption.

## Customization

- **Shift Value**: You can experiment with different shift values to see how they affect the encryption and decryption.
- **Mode Selection**: The script is set to encrypt first and then decrypt, but you can modify it to only perform one operation if needed.
.
