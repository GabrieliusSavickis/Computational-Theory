# Countdown Numbers Game Solver

This repository hosts a Python solution designed to solve the Countdown Numbers Game, a challenging segment from the TV show Countdown. Our solver tackles the computational intricacies involved in deriving either exact or approximate solutions using a set of numbers and arithmetic operations.

## Project Description

In the Countdown Numbers Game, contestants use six randomly chosen numbers and arithmetic operations (addition, subtraction, multiplication, and division) to hit a randomly generated target number. The game tests the optimization of operation sequences and the efficiency of problem-solving under tight constraints.

## Features

- **Solver Algorithm**: Employs both brute-force and heuristic methods to discover possible solutions.
- **Optimization Analysis**: Analyzes computational complexity and explores strategies to optimize the solving process.
- **Educational Tool**: Acts as a learning aid for understanding computational paradigms and algorithm design.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Git (for cloning the repository)

### Installation

Clone this repository to your local machine using:

```bash
git clone https://github.com/GabrieliusSavickis/Computational-Theory.git
```
Navigate to the project directory:
```
cd Computational-Theory
```

### Usage
Select an Anaconda kernel and Run All to see both Brute Force and Recursive components compile.

### How It Works
The `solve_numbers` function tries to find a valid sequence of operations that transforms a set of given numbers into the target number. 
It considers all permutations of numbers and operations, using a recursive strategy enhanced with memoization to improve performance.

### Acknowledgements
- Inspired by the official Countdown game show.
- Draws on computational theory resources from academic literature referenced in the countdown.ipynb file.


