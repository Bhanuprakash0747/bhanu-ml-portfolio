# 🔷 XOR Problem in Machine Learning

## 📌 Overview

The XOR (Exclusive OR) problem is a classic example in machine learning that highlights the limitations of simple linear models like the perceptron.

This project demonstrates:

* Why a **single-layer perceptron fails** to solve XOR
* Implementation from scratch using only NumPy

---

## 🧠 What is XOR?

XOR is a logical operation defined as:

| x1 | x2 | Output |
| -- | -- | ------ |
| 0  | 0  | 0      |
| 0  | 1  | 1      |
| 1  | 0  | 1      |
| 1  | 1  | 0      |

👉 Output is **1 when inputs are different**, otherwise 0.

---

## ❌ Why Perceptron Fails

A perceptron is a **linear classifier**, meaning it can only draw a single straight line as a decision boundary.

Mathematically:

* Decision boundary:

  w1x1 + w2x2 + b = 0

* Prediction depends on which side of the line the point lies.

### 🚫 Problem:

The XOR dataset is **not linearly separable**.

* Points (0,1) and (1,0) belong to class 1
* Points (0,0) and (1,1) belong to class 0

👉 No single straight line can separate these points.

### 🔴 Mathematical Insight:

When we try to satisfy all classification conditions, we get:

* b > 0
* b < 0

❌ Contradiction → No solution exists

---


## 🔥 Key Takeaways

* Perceptron can only learn **linear boundaries**
* XOR requires a **non-linear decision boundary**

---

## 👨‍💻 Author

Bhanu Prakash
Machine Learning Enthusiast | Exploring AI from fundamentals

---

## ⭐ If you found this useful

Give this repo a star ⭐ and connect with me on LinkedIn!
