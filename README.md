# Numerical Methods Web App 🧮🌐

A web-based application built with **Flask** to help users explore and calculate various **numerical methods** used in mathematics, engineering, and scientific computing.

## 📚 Features

This app provides a clean and interactive interface to experiment with the following numerical methods:

| Feature                     | Route                        | File                        |
|----------------------------|------------------------------|-----------------------------|
| Matrix Operations          | `/matrix`                    | `matrix.html`               |
| Matrix Inverse             | `/matrix-inverse`            | `matrix_inverse.html`       |
| LU Decomposition           | `/lu-decomposition`          | `lu_decomposition.html`     |
| Gauss Elimination          | `/gauss-elimination`         | `gauss_elimination.html`    |
| Iteration Method           | `/iteration-method`          | `iteration_method.html`     |
| Non-linear Equation Solver | `/non-linear`                | `non_linear.html`           |
| Interpolation              | `/interpolation`             | `interpolation.html`        |
| System Simulation          | `/system-simulation`         | `system_simulation.html`    |
| Monte Carlo Simulation     | `/monte-carlo`               | `monte_carlo.html`          |
| Markov Chain               | `/markov-chain`              | `markov_chain.html`         |

All pages inherit from `base.html` and are structured under the `templates/pages/` directory.

## 🚀 Getting Started

### Requirements

- Python 3.8+
- Flask

### Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/numerical-methods-flask.git
cd numerical-methods-flask
