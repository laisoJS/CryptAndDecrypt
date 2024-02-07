# CryptAndDecrypt

This repository contains a Python script for AES 256 encryption and decryption using the pycryptodomex library.

## Description

The script provides two main functions: `encrypt` and `decrypt`. 
The `encrypt` function takes a plain text and a password, and returns a dictionary with the encrypted text. 
The `decrypt` function takes an encrypted dictionary and a password, and returns the decrypted text.

## Installation

To run this script, you need to have Python installed on your machine along with the pycryptodomex library. You can install it using pip:

```bash
pip install pycryptodomex
```

## Usage

Run the script in your terminal. You will be presented with a menu to choose from:

0. Quit
1. Encrypt information
2. Decrypt information

Enter your choice, and follow the prompts.

## Example

On windows
```bash
python main.py
```
on Linux
```bash
chmod +x main.py
./main.py
```

## License

This project is licensed under the Unlicense.
This means the software is free and unencumbered software released into the public domain.

## Acknowledgments

This script is based on the tutorial from [HackerNoon](https://hackernoon.com/how-to-use-aes-256-cipher-python-cryptography-examples-6tbh37cr).
