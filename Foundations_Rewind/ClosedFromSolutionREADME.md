# Linear Regression using Closed Form Solution (Normal Equation)

This project implements **Linear Regression from scratch** using the **Closed Form Solution (Normal Equation)** without using libraries like Scikit-Learn or NumPy for matrix operations.

Instead of relying on built-in ML frameworks, this implementation focuses on understanding the mathematics behind how Linear Regression actually learns.

---

## Objective

The goal of this project is to:

* Understand Linear Regression mathematically
* Build matrix operations manually
* Learn how the Normal Equation works
* Compute model parameters directly without Gradient Descent

---

## Mathematical Formula

The Closed Form Solution for Linear Regression is:

[
\theta = (X^T X)^{-1} X^T y
]

Where:

* (X) → Design Matrix
* (X^T) → Transpose of Matrix
* (y) → Target values
* (\theta) → Learned parameters (weights & bias)

---

## What is Implemented?

This project manually implements:

* Design Matrix creation
* Matrix Transpose
* Matrix Multiplication
* 2x2 Matrix Inversion
* Closed Form Solution
* Prediction Function
* Mean Squared Error (MSE)

---

## Dataset Used

Sample Dataset:

| x | y |
| - | - |
| 1 | 2 |
| 2 | 3 |
| 3 | 5 |

---

## Learning Flow

```text
Raw Data
   ↓
Build Design Matrix X
   ↓
Compute Xᵀ
   ↓
Compute XᵀX
   ↓
Compute Xᵀy
   ↓
Compute (XᵀX)⁻¹
   ↓
Find θ
   ↓
Make Predictions
   ↓
Calculate MSE
```

---

## Final Learned Equation

The model learns a line of the form:

[
y = \theta_0 + \theta_1 x
]

For this dataset:

* Intercept ((\theta_0)) ≈ 0.333
* Slope ((\theta_1)) ≈ 1.5

Final Equation:

[
y = 0.333 + 1.5x
]

---

## Key Concepts Learned

### Design Matrix

Transforms raw features into matrix form for linear algebra operations.

### Matrix Transpose

Required for the Normal Equation.

### Matrix Inverse

Used to isolate the parameter vector (\theta).

### Closed Form Solution

Directly computes optimal parameters without iterative learning.

### Mean Squared Error (MSE)

Measures how well predictions match actual values.

---

## Why This Project?

Most tutorials teach Linear Regression using libraries.

This project focuses on:

* understanding the math,
* building intuition,
* and implementing everything manually from scratch.

---

## Future Improvements

* Support multiple features
* Add NumPy implementation
* Compare with Gradient Descent
* Visualize regression line
* Add larger datasets

---

## Tech Stack

* Python
* Pure Python Matrix Operations
* Linear Algebra Fundamentals

---

## Author

Built as part of my **ML Rewind** series — revisiting Machine Learning fundamentals deeply by implementing algorithms from scratch.
