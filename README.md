# Quadracrypt Cipher

Quadracrypt is a custom multi-layered cryptographic algorithm that combines Playfair Cipher, Caesar Cipher, shifting, and XOR operations to enhance data encryption and security. It is designed for learning and demonstrating the concept of layered encryption and custom ciphers.

## Objective

The aim of this project is to explore the combination of classical encryption techniques to create a more secure and complex cipher system. The focus is on understanding each algorithm’s role and the overall impact of layered encryption.

## Technologies Used

- Python (Core logic and implementation)
- Standard Libraries only (no external dependencies)

## Features

- Combines four encryption techniques: Playfair, Caesar, shift logic, and XOR
- Supports encryption and decryption of text messages
- Demonstrates the effect of layered encryption on data security
- Designed to be modular and extendable

## Encryption Flow

1. **Playfair Cipher** – Encrypts using a 5x5 matrix of letters.
2. **Caesar Cipher** – Shifts characters by a fixed value.
3. **Custom Shift Logic** – Applies a defined shifting algorithm.
4. **XOR Encryption** – Applies bitwise XOR to characters with a key.

Each layer adds complexity to the encryption, making brute-force attacks significantly harder.

## Getting Started

1. Clone the repository:

```bash

