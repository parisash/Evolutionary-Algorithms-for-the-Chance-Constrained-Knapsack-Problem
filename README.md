# Evolutionary Algorithms for the Chance-Constrained Knapsack Problem

This repository implements evolutionary algorithm approaches for solving the **Chance-Constrained Knapsack Problem (CCKP)** using Python and Jupyter Notebook.

The project explores how optimisation techniques can be applied to decision-making problems under uncertainty, where selected items must maximise value while satisfying probabilistic capacity constraints. This type of problem is relevant to real-world scenarios where decisions must balance benefit, limitation, uncertainty, and risk.

Although this is an earlier academic and research-focused project, it demonstrates my foundation in optimisation, Python-based experimentation, algorithmic thinking, and reproducible analytical workflows.

## Project Purpose

The goal of this project is to investigate how evolutionary algorithms can be used to solve a constrained optimisation problem where uncertainty is part of the decision process.

This project demonstrates:

* Evolutionary computation fundamentals
* Optimisation under uncertainty
* Python-based algorithm implementation
* Experimental design and performance comparison
* Constraint handling
* Reproducible analysis using Jupyter Notebook
* Analytical reasoning and problem-solving

## Problem Overview

The classic knapsack problem aims to select a subset of items that maximises total value while keeping total weight within a fixed capacity.

The **chance-constrained** version introduces uncertainty. Instead of requiring the constraint to always be satisfied deterministically, the solution must satisfy the constraint with a specified probability level.

In simple terms, the algorithm must find a strong solution that:

* Maximises total value
* Controls the probability of violating the capacity constraint
* Handles uncertainty in item weights, values, or constraints
* Balances performance and risk

## Why This Problem Matters

Chance-constrained optimisation is useful when decisions involve uncertainty and risk. Similar thinking can be applied in areas such as:

* Resource allocation
* Portfolio optimisation
* Cloud workload scheduling
* Cybersecurity risk prioritisation
* Operational planning
* Budget allocation
* Data-driven decision support
* Governance and risk-based control selection

This makes the project relevant beyond the original algorithmic problem, especially for roles involving analytics, risk, governance, and decision-support systems.

## Algorithms and Concepts

This project may include or support concepts such as:

* Evolutionary algorithms
* Genetic algorithms
* Population-based search
* Fitness functions
* Selection, crossover, and mutation
* Constraint handling
* Probabilistic feasibility
* Risk-aware optimisation
* Comparative performance analysis

## Technologies Used

* Python 3
* Jupyter Notebook
* NumPy
* pandas
* Matplotlib
* Randomised search / evolutionary computation logic

## Repository Structure

```text
Evolutionary-Algorithms-for-the-Chance-Constrained-Knapsack-Problem/
│
├── notebooks/              # Jupyter Notebook implementation
├── data/                   # Problem instances or generated datasets, if included
├── outputs/                # Results, charts, or experiment outputs
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies, if added
```

## How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Evolutionary-Algorithms-for-the-Chance-Constrained-Knapsack-Problem.git
cd Evolutionary-Algorithms-for-the-Chance-Constrained-Knapsack-Problem
```

Create and activate a virtual environment:

```bash
python -m venv venv
```

On Windows:

```bash
venv\Scripts\activate
```

On macOS/Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook file and run the cells step by step.

## Example Requirements File

If the repository does not already include a `requirements.txt`, one can be added with:

```text
numpy
pandas
matplotlib
jupyter
```

## Example Workflow

The project follows a typical optimisation experiment workflow:

1. Define the chance-constrained knapsack problem
2. Generate or load problem instances
3. Initialise a population of candidate solutions
4. Evaluate candidate fitness
5. Apply constraint-handling logic
6. Select stronger candidate solutions
7. Apply crossover and mutation
8. Repeat the evolutionary search process
9. Compare solution quality and feasibility
10. Analyse results and limitations

## Learning Outcomes

Through this project, I practised how to:

* Translate a mathematical optimisation problem into code
* Implement population-based search logic in Python
* Handle uncertainty and probabilistic constraints
* Design and run computational experiments
* Compare algorithm behaviour across iterations
* Interpret optimisation results
* Document algorithmic workflows in a reproducible format

## Relevance to My Current Career Direction

My current focus is cybersecurity GRC, cloud security, privacy governance, risk analytics, and AI assurance. This repository supports that direction by demonstrating my ability to work with optimisation, uncertainty, risk-aware decision-making, and Python-based analytical workflows.

These capabilities are relevant to modern security and governance work, where professionals often need to prioritise risks, allocate resources, assess trade-offs, and produce evidence-based recommendations under uncertainty.

## Future Improvements

Planned improvements for this repository include:

* Add clearer explanations of the chance-constrained knapsack problem
* Add diagrams explaining the optimisation workflow
* Add experiment result tables
* Add convergence charts
* Add comparison between different evolutionary strategies
* Add a cleaner `requirements.txt`
* Add comments and markdown explanations inside notebooks
* Add a short case study connecting the optimisation logic to risk-based decision-making
* Improve reproducibility by documenting random seeds and experiment settings

## Author

**Parisa Shojaei**

## Note

This is an earlier academic and research-focused repository. It is being updated to better document the technical workflow, optimisation concepts, and practical relevance of the implementation.
