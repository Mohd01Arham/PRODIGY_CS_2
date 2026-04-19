Image Encryption Tool
A simple Python tool for encrypting and decrypting images using pixel manipulation.

Author
Created by: Ravindra Pandit Ahire
Task 2: Pixel Manipulation for Image Encryption - Completed
Directory Structure
PRODIGY_CS_2/
├── image_encryption.py    # Main encryption/decryption script
├── requirements.txt       # Project dependencies
└── README.md             # Project documentation
Features
Encrypt images by applying XOR operation to each pixel
Decrypt images using the same key
Simple command-line interface
Supports common image formats (JPG, PNG, etc.)
Automatic filename generation for encrypted/decrypted images
Installation
Make sure you have Python 3.10 or 3.11 installed
Install the required dependencies:
pip install -r requirements.txt
Usage
Run the script:

python image_encryption.py
Choose an option:

1: Encrypt Image
2: Decrypt Image
Enter the path of the input image

The encrypted/decrypted image will be automatically saved with "_encrypted" or "_decrypted" suffix
How It Works
The tool uses a simple XOR operation with a key to encrypt and decrypt images:

Each pixel's RGB values are XORed with the key
The same key is used for both encryption and decryption
The default key is 0x55 (85 in decimal)
Security Note
This is a basic encryption method for educational purposes. For real-world applications, consider using more secure encryption methods.

Example
Encrypt an image:

Input: profile_1.jpg
Output: profile_1_encrypted.jpg
Decrypt the image:

Input: profile_1_encrypted.jpg
Output: profile_1_encrypted_decrypted.jpg# PRODIGY_CS_2
task 2
