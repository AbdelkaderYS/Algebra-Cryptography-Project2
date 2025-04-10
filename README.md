# Algebra and Cryptography Project2

This repository contains implementations of various cryptographic algorithms and mathematical techniques developed as part of the Algebra and Cryptography course at the African Institute for Mathematical Sciences (AIMS), Kigali, Rwanda.

## Overview

This project covers three main exercises:

1. **Sieve of Eratosthenes**: Implementation of the classical prime number sieve algorithm
2. **ElGamal Decryption**: Decryption of an intercepted message using the ElGamal cryptosystem
3. **ElGamal Implementation**: Complete implementation of the ElGamal encryption system with custom prime generation

## Requirements

- Python 3.6+
- Required packages:
  - `numpy`
  - `sympy`
  - `matplotlib`

## Installation

```bash
git clone https://github.com/yourusername/Algebra-Cryptography-Assignment.git
cd Algebra-Cryptography-Assignment
pip install -r requirements.txt
```

## Exercise Details

### Exercise 1: Sieve of Eratosthenes

Implementation of the classic prime number generation algorithm, used to:
- Find the 13,181,999th prime number
- Count the number of primes between 2^25 and 2^26

### Exercise 2: ElGamal Decryption

Decrypting a message encrypted with the ElGamal cryptosystem using:
- Discrete logarithm techniques
- Chinese Remainder Theorem
- Pohlig-Hellman algorithm

### Exercise 3: ElGamal Implementation

Implementation of a complete ElGamal cryptosystem with:
- Generation of large safe primes of the form p = 2*p1*p2 + 1
- Key generation, encryption, and decryption operations

## Author

Abdelkader YOUNOUSSI SALEY
African Institute for Mathematical Sciences
Kigali, Rwanda
