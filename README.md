# SCT_CS_02
A lightweight Python GUI application for encrypting and decrypting images using two simple techniques: XOR operation and pixel swapping. This tool is built with Tkinter for the interface and PIL (Pillow) for image processing.
 Image Encryption Tool

 Image Encryption Tool

A lightweight Python GUI application to encrypt and decrypt images using two simple methods: XOR operation and pixel swapping. This tool is ideal for educational purposes and basic image obfuscation.

 Features

- Encrypt and decrypt images using:
  - XOR operation with a user-defined key
  - Pixel swapping algorithm
- Supports common image formats: `.jpg`, 
- Simple and intuitive Tkinter-based GUI
- No external dependencies beyond PIL and NumPy

 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/limitless002/image-encryption-tool.git
   cd image-encryption-tool

- Install dependencies:
pip install pillow numpy
- Run the application:
python image_encryption_tool.py
 Usage- Launch the GUI.
- Click Browse to select an image file.
- Choose the encryption method:
- xor: requires a numeric key.
- swap: no key needed.
- Click Encrypt to save the encrypted image.
- Click Decrypt to reverse the process.
Note: XOR encryption is symmetric. Use the same key for both encryption and decryption.📷 Example- Original image: photo.jpg
- Encrypted output: photo_encrypt.png
- Decrypted output: photo_decrypt.png
  
📂 File Structureimage-encryption-tool/
├── image_encryption_tool.py   # Main application script
├── README.md                  # Project documentation
   Limitations- XOR encryption is not secure for sensitive data.
- Pixel swapping is reversible but not cryptographically strong.
- Designed for educational and demonstration purposes.
