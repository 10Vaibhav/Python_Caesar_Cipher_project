# Caesar Cipher

A Python implementation of the classic Caesar Cipher encryption and decryption technique.

## Description

This program allows users to encode or decode messages using the Caesar Cipher method. It shifts the letters of the alphabet by a specified amount to create an encoded message or decode an existing one.

## Features

- Encode and decode messages
- Custom shift amount
- Handles non-alphabetic characters
- ASCII art logo
- Option to continue encoding/decoding multiple messages

## Files

- `caesar_cipher.py`: Main script containing the cipher logic and user interface
- `Art_cipher.py`: Contains ASCII art logo for the program

## Requirements

- Python 3.x

## Follow the on-screen prompts:
1. Choose to 'encode' or 'decode' a message
2. Enter the message
3. Specify the shift number
4. View the result
5. Choose to continue or exit

## How It Works

- Encoding: Each letter in the message is shifted forward in the alphabet by the specified amount.
- Decoding: Each letter in the message is shifted backward in the alphabet by the specified amount.
- Non-alphabetic characters remain unchanged.
- The shift wraps around the alphabet (e.g., shifting 'z' by 1 results in 'a').

## Contributing

Contributions, issues, and feature requests are welcome.
