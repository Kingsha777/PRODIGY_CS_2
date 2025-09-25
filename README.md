# Image Encryption and Decryption using Pixel Manipulation

This Python script allows you to encrypt and decrypt images using a simple pixel manipulation technique based on XOR operations. The script uses the `Pillow` library for image processing and `numpy` for efficient array manipulation.

## Features
- **Encrypt an Image:** XORs each pixel of the image with a key to create an encrypted version.
- **Decrypt an Image:** Reverses the encryption process by XORing the encrypted image with the same key.

## Requirements
- Python 3.x
- Pillow (for image processing)
- numpy (for numerical operations)

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Kingsha777/Image-decrypt.git
   cd image-decrypt
   Example
If you want to encrypt an image named example.png using a key of 123, the code snippet would look like:

python
Copy code
key = 123
encrypt_image('example.png', key)
decrypt_image('encrypted_image.png', key)
