# Computational Mathematics — Assignments (AITU)

Six Jupyter notebooks covering root-finding, linear-system solvers, matrix inversion, curve fitting, interpolation, and numerical differentiation.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter) ![NumPy](https://img.shields.io/badge/NumPy-grey?logo=numpy) ![SciPy](https://img.shields.io/badge/SciPy-grey?logo=scipy)

---

## Overview

This repository contains six graded assignments from the Computational Mathematics course at Astana IT University. Each notebook implements numerical algorithms from scratch (using NumPy) and verifies results against analytical or library-based references.

---

## What it covers

| Assignment | Numerical methods implemented |
|---|---|
| **1** | Graphical root localization; bisection method; absolute error analysis |
| **2** | Jacobi iterative method for linear systems; diagonal-dominance check; convergence plots |
| **3** | Iterative matrix inversion (Schulz / Newton–Schulz iteration); comparison with `numpy.linalg.inv` |
| **4** | Linear, polynomial (quadratic), and exponential curve fitting; three-parameter law fitting; forward difference table |
| **5** | Newton's forward interpolation; Newton's backward interpolation; central difference interpolation |
| **6** | First and second derivatives via Newton's forward/backward difference formulas |

---

## Notebooks

| File | Description |
|---|---|
| `Assignment_1_CM.ipynb` | Root finding: graphical method + bisection; absolute error |
| `Assignment_2_CM.ipynb` | Jacobi method for 3×3 system; convergence analysis |
| `Assignment_3_CM.ipynb` | Iterative matrix inversion; convergence check vs NumPy |
| `Assignment_4_CM.ipynb` | Curve fitting (linear, quadratic, exponential, 3-constant law); finite difference table |
| `Assignment_5_CM.ipynb` | Newton forward/backward/central interpolation formulas |
| `Assignment_6_CM.ipynb` | Numerical differentiation (1st and 2nd derivatives) via finite differences |

---

## Getting started

```bash
# 1. Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# 2. Install dependencies
pip install jupyter numpy scipy matplotlib

# 3. Open any notebook
jupyter lab Assignment_1_CM.ipynb
```

---

Adil Ormanov — [GitHub](https://github.com/Adilforest)
