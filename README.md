# Optimization Problem Solving Network (OPSN)

## Intro

Optimization problems play a crucial role in scientific research and engineering. This project presents the Optimization Problem Solving Network (OPSN), a new neural network design aimed at solving these challenges effectively.

OPSN formulates optimization problems using a dedicated neural network. We tested its performance on 15 CEC2017 benchmark functions and six real-world engineering problems, comparing the results with four other optimization algorithms.

Our findings show that OPSN outperforms existing methods, achieving faster convergence and greater versatility, making it a strong solution for optimization tasks.



## Features

- **Input Handling**: Normalizes input data containing features such as position and velocity.
- **Path Calculation**: Computes path positions from starting to ending points, incorporating multiple control points.
- **Threat Detection**: Evaluates threat levels based on distances to circular threat objects.
- **Path Optimization**: Aggregates threat data to determine the safest and most efficient path.
- **Output Generation**: Provides the weighted path length for further decision-making processes.

## Installation

To install the required dependencies, you can use pip:

```bash
pip install -r requirements.txt
