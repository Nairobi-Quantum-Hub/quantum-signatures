# Quantum Signatures: A Quantum Security Encryption Algorithm

This repository contains a Qiskit-based implementation of the Quantum Signatures algorithm, which utilizes quantum principles for secure encryption. The algorithm transforms a user's drawn signature into quantum states, extracting private and public keys through geometric and quantum operations, and ensuring secure document decryption.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Quantum Algorithm Overview](#quantum-algorithm-overview)
- [Visualizations](#visualizations)
- [Decryption](#decryption)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Quantum Signatures is a quantum security encryption algorithm that operates on a signature drawn on a Cartesian plane. The algorithm extracts a private key and a public key from the signature path, encodes them into quantum states, and uses quantum superposition and gate rotations for encryption. The public key is compared against the transformed private key to decrypt documents securely.

## Features

- **Quantum Encryption**: Utilizes quantum gates, including rotation and Hadamard gates, for secure encryption.
- **Key Extraction**: Derives private and public keys from a user's signature.
- **Quantum State Visualization**: Provides visualizations of quantum states through Bloch spheres and histograms.
- **Decryption Check**: Compares the public key with the measured quantum state to determine if decryption is successful.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/quantum-signatures.git
   cd quantum-signatures

