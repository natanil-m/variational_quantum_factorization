# Quantum Factorization - Shallow Depth Factoring (SDF)

## Paper 
https://arxiv.org/abs/2305.19542

## Overview

Large integer factorization is a challenging problem, especially in the realm of quantum computing. Classical methods for computing prime factors suffer from exponential time complexity. However, with quantum computing, there is immense potential for achieving faster computational processes.

We present the Shallow Depth Factoring (SDF) algorithm, a novel quantum approach to factor large integers efficiently. The SDF algorithm consists of three key steps:

1. Conversion: Transforming the factoring problem into an optimization problem without an objective function.
2. Quantum Feasibility Labeling (QFL): Labeling all potential solutions based on their feasibility for the optimization problem.
3. Variational Quantum Search (VQS): Utilizing VQS to find all feasible solutions efficiently.

## Benefits
- Linear Scalability: The circuit depth of the shallow-depth quantum circuits scales linearly with the size of the integer to be factorized.
- Enhanced Feasibility: By minimizing the number of gates in the circuit, our algorithm improves feasibility and reduces vulnerability to errors.

# Examples

## Example 1
### This Example is for number = 143.
![Example1](https://github.com/natanil-m/variational_quantum_factorization/blob/main/figure_example1.png)

## Example 2
### This Example is for number = 391.
![Example2](https://github.com/natanil-m/variational_quantum_factorization/blob/main/figure_example2.png)

## Example 3
### This Example is for number = 323.
### After prepocessing we reduce the equestions as following:
![Eq_Example3](https://github.com/natanil-m/variational_quantum_factorization/blob/main/equations_example3.png)
![Example3](https://github.com/natanil-m/variational_quantum_factorization/blob/main/figure_example3.png)


## Contribution

We welcome contributions to enhance the algorithm, improve efficiency, or add new features. Please feel free to open issues or submit pull requests.
