# p-Median and Maximal Coverage Location Problems

This repository contains solutions to the p-Median and Maximal Coverage Location problems. The objective function, sets, parameters, and constraints are defined both visually and mathematically.

## Problem Description

The p-Median problem involves selecting p facilities from a set of locations to minimize the total cost of serving customers. The Maximal Coverage Location problem involves selecting locations to maximize the coverage of customers, subject to constraints on the number of facilities that can be opened.

## Tools

The problems are solved using the following solvers:

- **gurobipy**: A Python interface for Gurobi, an optimization solver.
- **pyomo**: A Python-based, open-source optimization modeling language.
- **ipopt**: Interior Point OPTimizer, a software package for large-scale nonlinear optimization.

## Contents

- `Cordero-Lucia-HW2.ipynb`: Contains the source code for solving the problems.
- `examples/`: Contains example input data and scripts for running the solvers.
- `docs/`: Contains documentation on the problem formulations and solution approaches.

## Usage

To use the solvers, install the required dependencies and run the scripts in the `examples/` directory.

```bash
pip install gurobipy pyomo ipopt
python examples/run_solver.py
```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
Feel free to customize it further to match your repository's specific details and needs!
