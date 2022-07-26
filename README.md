# Hybrid Quantum Portfolio Optimization
## Endowment Portfolio Analysis

This repository utilizes gate model quantum computing, making use of the qiskit framework, to analyze an endowment portfolio.

The problem is cast as a Quadratic Unconstrained Binary Optimization (QUBO) problem, which takes into account the yield of the portfolio and the risk / relationship between asset returns, with a budget constraint. 

This qubo is solved by the Variational Quantum Eigensolver (VQE) and Quantum Approximate Optimization Algorithm (QAOA), to select the best $B$ assets from a total of $n$ assets. 

From here, risk-parity analysis is used to weight the assets in the portfolio. An extension of this work could explore developing the QUBO to include transaction costs, a more sophisticated measure of risk, etc.
