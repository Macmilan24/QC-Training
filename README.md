# Quantum Computing Assignment

This repository contains my solutions for the Quantum Computing Assignment, implemented using Qiskit in a Google Colab notebook. The notebook (`Samuel Dagne Task-QC-Training.ipynb`) includes code, visualizations, and explanations for all tasks.

## Tasks Overview

### Task 1: Quantum Circuit with Hadamard Gate
- Created a single-qubit circuit.
- Applied a Hadamard gate to create superposition.
- Measured the qubit and visualized the results with a histogram, showing 50% |0⟩ and 50% |1⟩.

### Task 2: Quantum Coin Flip
- Used a single qubit with a Hadamard gate to simulate a fair coin flip.
- Measured the qubit, mapping |0⟩ to Heads and |1⟩ to Tails.
- Printed the probabilities and showed the results in a histogram.

### Task 3: Bell State (Entanglement)
- Created a two-qubit circuit.
- Applied a Hadamard gate to the first qubit and a CNOT gate to entangle the qubits.
- Measured both qubits, showing correlation (|00⟩ or |11⟩) in the histogram.

### Task 4: Generate the Plus State |+⟩
- Prepared the |+⟩ state (1/√2)(|0⟩ + |1⟩) using a Hadamard gate on a single qubit.
- Measured the qubit to confirm the 50/50 distribution with a histogram.

### Task 5: Theory Check-ins
- Answered three questions on superposition, interference, and measurement in quantum computing, explaining their roles in quantum algorithms.

## How It Was Done
- The code follows a format using Qiskit and `SamplerV2` for simulations.
- Each task includes a quantum circuit, simulation with 128 shots, and a histogram of results.
- The notebook was created in Google Colab, run to generate outputs, and uploaded here.

## Running the Notebook
- Open `Samuel Dagne Task-QC-Training.ipynb` in Google Colab.
- Run the cell to install Qiskit, execute the circuits, and view the results.
