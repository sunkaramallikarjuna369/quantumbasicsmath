# Quantum Computing Visualizations

Interactive HTML visualizations for understanding quantum computing fundamentals, culminating in the Deutsch-Jozsa algorithm.

## Overview

This project provides comprehensive, interactive visualizations that explain quantum computing concepts from the ground up. Each visualization is a standalone HTML file that runs directly in your browser - no installation required.

## Quick Start

### Option 1: Download and Open Locally

1. **Download the repository:**
   ```bash
   git clone https://github.com/sunkaramallikarjuna369/quantumbasicsmath.git
   ```
   Or download as ZIP from the GitHub page and extract.

2. **Open any HTML file in your browser:**
   - Navigate to the downloaded folder
   - Double-click any `.html` file to open it
   - Or right-click → "Open with" → Choose your browser

3. **Start with the basics:**
   - Begin with `01_quantum_states/01_basis_states.html`
   - Follow the navigation links at the bottom of each page

### Option 2: Direct Browser Access

If the repository is hosted on GitHub Pages, you can access the visualizations directly at:
`https://sunkaramallikarjuna369.github.io/quantumbasicsmath/`

## Folder Structure

The visualizations are organized in sequential folders, designed to be followed in order:

### 01_quantum_states/
Foundation of quantum computing - understanding qubits and their states.

| File | Topic |
|------|-------|
| `01_basis_states.html` | Basis states \|0⟩ and \|1⟩, Bloch sphere introduction |
| `02_superposition.html` | Quantum superposition, the \|+⟩ state, measurement |
| `03_complex_amplitudes.html` | Complex numbers, phases, and interference |

### 02_quantum_operations/
Mathematical operations on quantum states.

| File | Topic |
|------|-------|
| `01_inner_product.html` | Inner product ⟨φ\|ψ⟩, overlap and probability |
| `02_outer_product.html` | Outer product \|φ⟩⟨ψ\|, operator construction |
| `03_tensor_product.html` | Tensor product ⊗, multi-qubit systems |

### 03_quantum_gates/
Single-qubit quantum gates and their effects.

| File | Topic |
|------|-------|
| `01_pauli_gates.html` | Pauli X, Y, Z gates and identity |
| `02_hadamard_gate.html` | Hadamard gate, creating superposition |

### 04_evaluation/
Verifying and understanding quantum properties.

| File | Topic |
|------|-------|
| `01_normalization.html` | Normalization condition, Born rule |
| `02_unitarity.html` | Unitary operators, reversibility |
| `03_eigenvalues.html` | Eigenvalues and eigenvectors |

### 05_circuits/
Building quantum circuits with multiple qubits.

| File | Topic |
|------|-------|
| `01_multi_qubit.html` | Multi-qubit systems, tensor products of gates |
| `02_oracle_construction.html` | Quantum oracles, phase kickback |

### 06_algorithm/
The Deutsch-Jozsa algorithm - putting it all together.

| File | Topic |
|------|-------|
| `01_deutsch_jozsa.html` | Complete Deutsch-Jozsa algorithm walkthrough |

## Local Implementation Guide

### System Requirements

- **Any modern web browser:** Chrome, Firefox, Safari, Edge (2020 or later)
- **No server required:** All files run locally using HTML5 Canvas
- **No dependencies:** Pure HTML, CSS, and JavaScript

### Running Locally

1. **Clone or download the repository:**
   ```bash
   git clone https://github.com/sunkaramallikarjuna369/quantumbasicsmath.git
   cd quantumbasicsmath
   ```

2. **Open files directly:**
   ```bash
   # On macOS
   open 01_quantum_states/01_basis_states.html
   
   # On Linux
   xdg-open 01_quantum_states/01_basis_states.html
   
   # On Windows
   start 01_quantum_states/01_basis_states.html
   ```

3. **Or use a local server (optional, for development):**
   ```bash
   # Using Python 3
   python -m http.server 8000
   # Then open http://localhost:8000 in your browser
   
   # Using Node.js
   npx serve .
   ```

### Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 80+ | Fully supported |
| Firefox | 75+ | Fully supported |
| Safari | 13+ | Fully supported |
| Edge | 80+ | Fully supported |

### Features

Each visualization includes:

- **Interactive Canvas Graphics:** Bloch spheres, state vectors, probability bars
- **Animated Transitions:** Watch quantum operations in action
- **Mathematical Equations:** Clear notation with explanations
- **Python Code Examples:** Corresponding NumPy implementations
- **Navigation Links:** Easy progression through topics

## Learning Path

For the best learning experience, follow this recommended order:

1. **Quantum States** (Folder 01)
   - Understand what a qubit is
   - Learn about superposition
   - Explore complex amplitudes

2. **Quantum Operations** (Folder 02)
   - Master inner and outer products
   - Understand tensor products for multi-qubit systems

3. **Quantum Gates** (Folder 03)
   - Learn the fundamental gates (X, Y, Z, H)
   - See how gates transform states on the Bloch sphere

4. **Evaluation** (Folder 04)
   - Verify normalization and unitarity
   - Understand eigenvalues and measurement

5. **Circuits** (Folder 05)
   - Build multi-qubit circuits
   - Learn about quantum oracles

6. **Algorithm** (Folder 06)
   - See the complete Deutsch-Jozsa algorithm
   - Understand quantum speedup

## Corresponding Notebook

These visualizations accompany the `deutsch_jozsa.ipynb` Jupyter notebook, which contains the Python/NumPy implementations of all concepts covered.

## Contributing

Contributions are welcome! Feel free to:
- Report bugs or issues
- Suggest new visualizations
- Improve existing explanations
- Add more quantum algorithms

## License

This project is open source and available for educational purposes.

## Acknowledgments

Created as an educational resource for understanding quantum computing fundamentals through interactive visualization.
