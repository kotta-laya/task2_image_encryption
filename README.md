# 🖼️ Image Encryption Tool

A browser-based image encryption tool using pixel manipulation with XOR encryption.

## Features

- Encrypt images using XOR operation on RGB values
- Decrypt images using the same key
- Supports JPEG, PNG, JPG formats
- Download encrypted/decrypted images
- Side-by-side original vs processed view

## How to Use

1. Click "Select Image" to choose an image
2. Enter an encryption key (1-255)
3. Click "Encrypt Image" to encrypt
4. Click "Decrypt Image" to restore (using same key)
5. Click "Download" to save the result

## How It Works

This tool uses XOR encryption on each pixel's RGB values. Each color channel (Red, Green, Blue) is XORed with your key. Since XOR is reversible, the SAME key encrypts AND decrypts the image.

## Technologies Used

- HTML5
- CSS3
- JavaScript (Canvas API)
- XOR Encryption Algorithm

## Author

Kotta Laya - Skill Craft Technology Intern

## Date

May 2026