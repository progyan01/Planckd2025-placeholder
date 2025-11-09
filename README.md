# Planck'd 2025 - Quantum Algorithms Track

**Repository for Team: `placeholder`**

- **Members:** Pragyan Ojha

---

## Project Summary


We implemented and analyzed three problems:

1.  **Problem 0: The Classical Random Walk**
    - Simulated a classical random walk for 10,000 walkers.
    - Confirmed that the RMS displacement follows a **diffusive** $\sqrt{t}$ spread.

2.  **Problem 1: A Quantum Coin Flip**
    - Simulated a walk using a Pauli-X gate.
    - Demonstrated that without superposition, the walk is just a simple, deterministic oscillation ($0 \to 1 \to 0 \to 1...$), not a true quantum walk.

3.  **Problem 2: The Superposed Walker**
    - Implemented a discrete-time one-dimensional quantum walk using a Hadamard gate as the coin-flip operator.
    - Built a hybrid simulation using **NumPy** to manage the state vector of amplitudes and **Qiskit** to provide the coin-flip operator.
    - Results show that the RMS displacement grows **linearly** ($\propto t$), confirming quadratic speedup over the classical walk.
    - Analyzed the position amplitudes, showing how quantum interference and superposition work together to create this unique behavior.
