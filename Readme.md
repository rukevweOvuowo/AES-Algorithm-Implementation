# AES Algorithm Implementation

A comprehensive implementation and analysis of the Advanced Encryption Standard (AES) algorithm, covering encryption, decryption, key generation, and comparison with cryptographic libraries.

## Overview

This project implements the AES symmetric block cipher algorithm from scratch, following the FIPS-197 specification. The implementation includes key schedule generation, encryption and decryption processes, and comparative analysis with established cryptographic libraries like PyCryptodome.

## Background

The Advanced Encryption Standard (AES) is a FIPS-approved cryptographic algorithm used to protect electronic data. As a symmetric block cipher, AES can encrypt and decrypt information using the same key. It transforms plaintext into unintelligible ciphertext during encryption and reverses the process during decryption.

## Requirements

- Python 3.x
- PyCryptodome library
- numpy (optional, for matrix operations)

## Project Structure

### Part A: Encryption Implementation

**Round-Key Generation**
- Master key expansion algorithm
- Generation of all encryption round keys
- Key schedule analysis and verification

**Core Encryption Functions**
- SubBytes transformation
- ShiftRows operation
- MixColumns transformation
- AddRoundKey operation

### Part B: Decryption Implementation

**Inverse Operations**
- InvSubBytes transformation
- InvShiftRows operation
- InvMixColumns transformation
- Reverse round key application

### Part C: Library Comparison

**PyCryptodome Integration**
- Standard AES implementation comparison
- Performance analysis
- Different modes of operation exploration

## Key Learning Objectives

### Cryptographic Understanding
- AES algorithm structure and design principles
- Round function transformations
- Key schedule generation process
- Security properties of symmetric block ciphers

### Implementation Skills
- Low-level cryptographic algorithm implementation
- Bitwise operations and finite field arithmetic
- Algorithm optimization and verification

### Practical Applications
- Comparison between custom and library implementations
- Understanding different AES modes of operation
- Performance and security trade-offs

## Analysis Questions Addressed

1. **Key Generation Analysis**: Testing different master keys and verifying round key generation
2. **Implementation Verification**: Ensuring correct encryption/decryption functionality
3. **Library Comparison**: Comparing custom implementation with PyCryptodome results
4. **Mode Exploration**: Analysis of different AES operation modes

## Security Considerations

- Implementation follows FIPS-197 specification
- Proper handling of key material

## References

- [NIST FIPS-197 AES Specification](https://nvlpubs.nist.gov/nistpubs/fips/nist.fips.197.pdf)
- [PyCryptodome Documentation](https://pycryptodome.readthedocs.io/en/latest/src/introduction.html)

## License

Educational implementation for cryptography learning purposes. 
