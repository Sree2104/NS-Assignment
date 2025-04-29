# 🔐 RSA Encryption & Decryption in Python

This project demonstrates a simple implementation of the **RSA algorithm** in Python using the `sympy` library for prime generation.

## 🚀 Features

- Key generation using large prime numbers
- Public and private key creation
- Message encryption and decryption
- Console-based user interaction

## 🔧 How It Works

1. **Generate Primes**: Uses `sympy.randprime()` to generate two large primes.
2. **Compute Keys**: Calculates modulus `n`, totient `phi(n)`, public key `(e, n)`, and private key `(d, n)`.
3. **Encrypt**: Converts message to an integer, encrypts with public key using `pow()`.
4. **Decrypt**: Decrypts with private key and converts back to the original string.

## 📦 Requirements

Install the required library:
```bash
pip install sympy
