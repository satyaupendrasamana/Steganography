Image Encryption and Decryption Tool

Project Overview

This project is designed to demonstrate the principles of image encryption and decryption using Python. It secures image files by encrypting them with a custom algorithm and provides a corresponding decryption process to restore the original image.

Files in the Repository

image_encryption.py - Python script to encrypt image files.

image_decryption.py - Python script to decrypt previously encrypted image files.

output_image.jpg - Sample output image used to demonstrate the encryption and decryption process.

Internship Project Submission PPT (2) (1) (1) (2).pptx - Presentation detailing the project's purpose, methodology, and outcomes.

ben stokes.jpg - Sample input image used in the encryption process.

Requirements

To run this project successfully, you will need:

Python 3.x

Libraries:

cryptography

PIL (Pillow)

pip install cryptography pillow

To install the required libraries, use the following command:

How to Run

Step 1: Image Encryption

Open the terminal or command prompt.

Navigate to the project folder.

Run the following command:

python image_encryption.py

Follow the prompts to select the image file you want to encrypt.

An encrypted image file will be generated.

Step 2: Image Decryption

Open the terminal or command prompt.

Navigate to the project folder.

Run the following command:

python image_decryption.py

Follow the prompts to select the encrypted image file.

The decrypted image will be saved as output_image.jpg.

Encryption Algorithm Overview

The encryption method uses Fernet encryption from the cryptography library to ensure strong security.

The encryption process converts image data into binary format, encrypts it, and saves it with a .enc extension.

Decryption Process

The decryption script takes the encrypted file, decodes the binary data, and reconstructs the original image format.

Project Presentation

The included PowerPoint presentation outlines the project details, including:

Introduction to encryption and decryption

Step-by-step explanation of the code logic

Demonstration of sample encrypted and decrypted images

Key challenges faced and solutions implemented

Future Improvements

Adding a GUI interface for improved user experience.

Implementing multiple encryption algorithms for enhanced security.

Introducing password protection for additional security layers.

Credits

This project was developed as part of my Cybersecurity Internship at APSSDC.

For any queries or improvements, feel free to contribute or contact me!
