# 🔐 Cryptography Toolkit

A comprehensive educational repository demonstrating modern cryptographic algorithms and security protocols through interactive Jupyter notebooks. This project showcases practical implementations of symmetric encryption, asymmetric cryptography, digital signatures, hashing algorithms, and secure communication protocols.

[![Python](https://img.shields.io/badge/Python-3.12.7-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)

## Project Overview

This repository serves as a complete educational resource for understanding cryptographic fundamentals through hands-on implementation. Each algorithm is explained with theoretical background, practical examples, and real-world applications, making complex security concepts accessible and demonstrable.

## Repository Structure

```
cryptography-toolkit/
├── asymmetric/              # Public-key cryptography
│   ├── diffie_hellman_.ipynb    # Key exchange protocol
│   ├── ecc_.ipynb              # Elliptic Curve Cryptography
│   ├── elgamal.ipynb           # ElGamal encryption
│   └── rsa_.ipynb              # RSA encryption/decryption
├── digital_signatures/     # Authentication & integrity
│   ├── dsa_signature.ipynb     # Digital Signature Algorithm
│   └── rsa_signature.ipynb     # RSA digital signatures
├── hashing/                # Cryptographic hash functions
│   ├── argon2_.ipynb           # Password hashing (Winner PHC 2015)
│   ├── bcrypt_.ipynb           # Adaptive hash function
│   ├── hmac_.ipynb             # Message authentication codes
│   ├── md5_.ipynb              # Legacy hash (educational)
│   ├── scrypt_.ipynb           # Memory-hard key derivation
│   ├── sha256_.ipynb           # SHA-2 family
│   └── sha3_.ipynb             # Keccak-based hashing
├── modes/                  # Encryption modes & ciphers
│   ├── cbc_.ipynb              # Cipher Block Chaining
│   ├── cfb_.ipynb              # Cipher Feedback
│   ├── chacha20_.ipynb         # Modern stream cipher
│   ├── ctr_.ipynb              # Counter mode
│   ├── ecb_.ipynb              # Electronic Codebook
│   ├── gcm_.ipynb              # Galois/Counter (AEAD)
│   ├── ofb_.ipynb              # Output Feedback
│   └── rc4_.ipynb              # Stream cipher (legacy)
├── symmetric/              # Secret-key cryptography  
│   ├── 3des_.ipynb             # Triple DES
│   ├── aes_.ipynb              # Advanced Encryption Standard
│   └── des_.ipynb              # Data Encryption Standard
└── tls/                    # Transport Layer Security (Future)
```

## Technologies & Skills Demonstrated

### **Cryptographic Expertise**
- **Symmetric Encryption**: AES, DES, 3DES with various operation modes
- **Asymmetric Cryptography**: RSA, ECC, ElGamal, Diffie-Hellman key exchange
- **Digital Signatures**: RSA-PSS, DSA, ECDSA, Ed25519
- **Hash Functions**: SHA-256/SHA-3, MD5, HMAC for integrity verification
- **Password Security**: Argon2, bcrypt, scrypt with proper salt handling
- **Modern Ciphers**: ChaCha20, AES-GCM for authenticated encryption

### **Programming & Development**
- **Python**: Advanced cryptographic library usage (`cryptography`, `pycryptodome`)
- **Jupyter Notebooks**: Interactive documentation and live demonstrations
- **Security Best Practices**: Proper key management, timing attack prevention
- **Algorithm Analysis**: Performance evaluation and security considerations

### **Industry Standards & Protocols**
- **TLS/HTTPS**: Understanding of web security protocols
- **PKI**: Public Key Infrastructure and certificate management
- **NIST Standards**: Implementation of government-approved algorithms
- **Real-world Applications**: Blockchain, VPNs, secure messaging

## Key Features

### **Educational Excellence**
- **Interactive Learning**: Each notebook combines theory with executable code
- **Visual Demonstrations**: Clear explanations with communication flow diagrams
- **Security Analysis**: Vulnerability discussions and mitigation strategies
- **Best Practices**: Industry-standard implementations with proper error handling

### **Professional Implementation**
- **Production-Ready Code**: Uses vetted cryptographic libraries
- **Security Warnings**: Clear guidance on deprecated/insecure algorithms
- **Parameter Guidance**: Recommended key sizes and configuration values
- **Real-World Context**: Applications in modern systems (Signal, Bitcoin, TLS)

### **Comprehensive Coverage**
- **Historical Perspective**: Evolution from DES to modern AES
- **Attack Vectors**: Understanding common cryptographic vulnerabilities
- **Performance Considerations**: Memory-hard functions vs. computational cost
- **Compliance**: FIPS-approved algorithms and enterprise requirements

## Quick Start

### Prerequisites
```bash
Python 3.12+
Jupyter Notebook
```

### Installation
```bash
# Clone the repository
git clone https://github.com/Imadjaha/cryptography-toolkit.git
cd cryptography-toolkit

# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```


## Learning Outcomes

After exploring this repository, you will understand:

- **Fundamental Cryptographic Principles**: Confidentiality, integrity, authenticity
- **Algorithm Selection**: When to use symmetric vs. asymmetric cryptography
- **Security Engineering**: Proper implementation of cryptographic protocols
- **Threat Modeling**: Understanding attack vectors and defensive measures
- **Industry Applications**: Real-world usage in modern secure systems

## Professional Impact

This project demonstrates:

### **Security Engineering Skills**
- Deep understanding of cryptographic fundamentals
- Ability to implement secure systems following industry standards
- Knowledge of common vulnerabilities and mitigation strategies

### **Technical Leadership**
- Complex technical concepts explained clearly for educational purposes
- Structured approach to learning and knowledge transfer
- Attention to security details and best practices

### **Industry Relevance**
- Coverage of algorithms used in major platforms (TLS, Bitcoin, Signal)
- Understanding of compliance requirements (FIPS, NIST standards)
- Practical knowledge applicable to cybersecurity, fintech, and enterprise systems

## Future Enhancements

- **TLS Protocol Implementation**: Complete handshake demonstration
- **Post-Quantum Cryptography**: NIST PQC competition winners
- **Zero-Knowledge Proofs**: Modern privacy-preserving techniques
- **Blockchain Applications**: Cryptocurrency and smart contract security
- **Side-Channel Analysis**: Timing and power analysis demonstrations

## Contributing

Contributions are welcome! 

---

*This repository demonstrates professional-level understanding of cryptographic systems and security engineering principles. Each implementation follows industry best practices and includes comprehensive documentation for educational and professional reference.*