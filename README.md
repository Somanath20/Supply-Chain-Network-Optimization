# Supply Chain Optimization with Linear Programming

This repository provides a Python-based framework for Supply Chain Network Design. It utilizes Linear Programming (LP) to determine the optimal locations for manufacturing facilities to minimize total costs while satisfying customer demand.

---

## Technical Methodology

The optimization model considers the following parameters to define the cost function and constraints:

* **Fixed Costs:** Monthly overhead for operating a facility ($/Month).
* **Variable Costs:** Production costs per unit ($/Unit).
* **Logistics Costs:** Shipping and transportation expenses from facilities to customers ($).
* **Demand Constraints:** Total customer requirements (Units) that must be met by the network.

---

## Project Structure

* `Supply Chain Optimization.ipynb`: Jupyter notebook containing the mathematical formulation and step-by-step data analysis.
* `supply_chain_optimization.py`: Standalone Python script for execution.

---

## Tech Stack & Dependencies

The project is built using the following libraries:

* **PuLP:** Linear Programming modeler for solving the optimization problem.
* **Pandas:** Data manipulation and processing of demand/cost matrices.
* **Openpyxl:** Engine for handling Excel-based input/output data.
* **Jupyter:** Interactive development and visualization environment.

---

## Getting Started

This project uses [uv](https://docs.astral.sh/uv/) for high-performance dependency management.

### Installation

```bash
# Install and sync dependencies
uv sync
```

```bash
uv run python supply_chain_optimization.py
```

```bash
uv run jupyter notebook
```