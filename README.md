# Image Encryption and Decryption
This repository contains a Python script that performs encryption and decryption of images using a combination of XOR, addition, and pixel shuffling techniques. The script uses the Python Imaging Library (PIL) and NumPy to manipulate image data.

# Features
Load Image: Converts an image file into a NumPy array for processing.
Encrypt Image: Encrypts the image using a combination of XOR operations, pixel value addition, and pixel shuffling.
Decrypt Image: Decrypts the image by reversing the encryption process.
Save Image: Converts the processed NumPy array back into an image and saves it to the specified path.
# Installation
To run this script, you need to have Python installed along with the following packages:

Pillow (Python Imaging Library)
NumPy
You can install these packages using pip:
pip install pillow numpy
# Usage

Clone the Repository:

git clone https://github.com/yourusername/image-encryption-decryption.git
cd image-encryption-decryption

Run the Script:


python image_encryption.py


Input Parameters:

The script will prompt you for the following input:

Path to the input image.

Path to save the encrypted image.

Path to save the decrypted image.

Two encryption keys (integers).

# Example:

If you have an image example.png in the current directory:

Enter the path to the input image: example.png

Enter the path to save the encrypted image: encrypted.png

Enter the path to save the decrypted image: decrypted.png

Enter the first encryption key (integer): 123

Enter the second encryption key (integer): 456

After running, the encrypted image will be saved as encrypted.png, and the decrypted image will be saved as decrypted.png.

# How It Works
Encryption:

The image is first XORed with key1.
Then, key2 is added to the pixel values.
The pixels are shuffled using a permutation based on key1.
Decryption:

The pixel shuffling is reversed.
key2 is subtracted from the pixel values.
The image is XORed again with key1 to retrieve the original image.
