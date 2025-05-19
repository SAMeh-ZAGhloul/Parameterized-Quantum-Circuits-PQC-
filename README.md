# Parameterized Quantum Circuits (PQC) for Binary Classification

This repository contains an implementation of a quantum binary classifier using Parameterized Quantum Circuits (PQC) with Qiskit.

## Installation

1. Clone this repository:
```bash
git clone https://github.com/SAMeh-ZAGhloul/Parameterized-Quantum-Circuits-PQC-.git
cd Parameterized-Quantum-Circuits-PQC-
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Overview

The implementation includes:
- Data preparation using scikit-learn's make_moons dataset
- Quantum circuit design with feature mapping and trainable ansatz
- Training using the COBYLA optimizer
- Evaluation metrics including confusion matrices
- Visualization of the decision boundary

## Requirements
- Qiskit
- NumPy
- scikit-learn
- Matplotlib

## Contents
- `pqc1.ipynb`: Jupyter notebook containing the complete implementation

## Features
- Implementation of ZZFeatureMap for data encoding
- RealAmplitudes ansatz for trainable parameters
- Visualization of quantum circuits
- Comprehensive evaluation metrics
- Decision boundary visualization
