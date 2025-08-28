# Quantum Chaos, Fractals & Randomness Generator

This repository contains a **quantum chaos and fractal-based randomness generator** built using [Qiskit](https://qiskit.org/).  
The code applies chaotic and fractal-inspired phase shifts on a quantum circuit, measures the output, and computes randomness metrics such as **Shannon entropy** and **fidelity**.  
It also generates **random bitstreams** and their **SHA-256 digest**, making it useful for randomness studies and cryptographic seed generation.  

---

## 🚀 Features
- Implements **chaotic + fractal phase encoding** on qubits  
- Runs on **IBM Quantum real hardware** (via IBM Runtime) or **AerSimulator**  
- Computes:
  - Shannon entropy of outcomes  
  - Fidelity to uniform distribution  
- Generates:
  - Raw bitstreams  
  - SHA-256 hash of bitstreams  
- Produces visualizations:
  - Quantum circuit diagram  
  - Measurement histogram  
  - Bloch sphere plots  

