# 🚀 Gradient Descent from Scratch (Linear Regression)

A simple implementation of Gradient Descent using NumPy to understand how machine learning models learn by minimizing error.

---

## 📊 Problem

Given a dataset:

X = [1, 2, 3, 4, 5]
y = [3, 4, 2, 4, 5]

Goal: Learn a function that predicts `y` from `x`.

---

## 🧠 Model

We use a linear model:

y = θ₀ + θ₁x

* θ₀ → intercept
* θ₁ → slope

---

## 📉 Loss Function

We measure error using Mean Squared Error (MSE):

J(θ₀, θ₁) = (1/m) Σ (y_pred - y)²

This tells how far predictions are from actual values.

---

## 🔁 How Gradient Descent Works

Instead of solving directly, the model learns iteratively:

1. Predict output
2. Calculate error
3. Compute gradients
4. Update parameters
5. Repeat

Update rule:

θ = θ - α · ∇J(θ)

---

## 💻 Implementation

* Built using NumPy
* No ML libraries used
* Includes:

  * Prediction step
  * Loss tracking
  * Gradient updates

---

## 📈 Results

After training:

* θ₀ ≈ 2.37
* θ₁ ≈ 0.41
* MSE ≈ 0.72

The model converges and finds the best-fit line for the data.

---

## 🔍 Observations

* Learning happens step by step
* Loss decreases over iterations
* Large errors are corrected early
* Later iterations refine the solution
* Data is not perfectly linear → model finds best approximation

---

## 💡 Key Insight

Gradient Descent is not about jumping to the answer.

It is a process of:

> continuous improvement driven by error

---

## 🚀 Next Steps

* Visualize loss vs iterations
* Experiment with different learning rates
* Extend to multiple features
* Compare with closed-form solution

---

## 📌 Conclusion

This project demonstrates how models learn from data by minimizing error iteratively, forming the foundation of many machine learning algorithms.

---

### 🔗 Connect

If you're also learning ML fundamentals, feel free to connect or share your thoughts.

#MachineLearning #GradientDescent #LinearRegression #MLRewind
