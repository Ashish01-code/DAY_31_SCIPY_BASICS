# DAY_31_SCIPY_BASICS
# Day 31 – SciPy Core Concepts: Sparse Matrices & Optimization

## Overview
This day focuses on understanding key SciPy modules used in Machine Learning and large-scale data processing. The goal is to learn how sparse data is efficiently stored, how optimization works behind ML algorithms, and how root-finding helps solve mathematical models.

This repository contains applied practice exercises, not production-level projects.

---

## Topics Covered

### 1. Sparse Matrices (CSR Format)
Real-world datasets often contain many zero values. Storing such data in dense format wastes memory and computation. SciPy provides sparse matrix representations to solve this problem efficiently.

- Dense vs Sparse data
- Compressed Sparse Row (CSR) matrix
- Memory-efficient storage
- Accessing sparse matrix components

Key Concepts:
- data → non-zero values
- indices → column indices
- indptr → row pointer index

Used Module:
scipy.sparse.csr_matrix

---

### 2. Optimization using scipy.optimize.minimize
Optimization is the backbone of Machine Learning. Model training is essentially minimizing a loss function.

In this task:
- A mathematical function is defined
- The minimum value is found numerically
- The optimal point is interpreted

Used Module:
scipy.optimize.minimize

This concept directly connects to:
- Gradient descent
- Loss minimization
- Model parameter tuning

---

### 3. Root Finding using scipy.optimize.root
Root finding is used to solve equations where the function output becomes zero. This is useful in mathematical modeling, optimization constraints, and scientific computing.

In this task:
- A nonlinear equation is defined
- Roots are computed numerically
- Results are validated

Used Module:
scipy.optimize.root

---

## Why This Matters for ML
- Sparse matrices are used in NLP, recommender systems, and high-dimensional datasets
- Optimization techniques train ML models
- Root solving supports advanced mathematical modeling

---

## Status
Day 31 completed.
Focus was on understanding concepts and applying them practically before moving deeper into Machine Learning models.
