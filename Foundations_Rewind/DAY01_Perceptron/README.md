\# 🧠 Day 01 — Perceptron (From Scratch)



\## 📌 What is a Perceptron?



The Perceptron is one of the simplest and earliest machine learning algorithms used for \*\*binary classification\*\*.



It is a \*\*linear classifier\*\* that separates data using a straight line (in 2D) or a hyperplane (in higher dimensions).



\---



\## ⚙️ How It Works



The perceptron computes a weighted sum of inputs and applies a step function:



z = w₁x₁ + w₂x₂ + ... + b  



ŷ = sign(z)



Where:

\- \*\*w\*\* → weights  

\- \*\*x\*\* → input features  

\- \*\*b\*\* → bias  

\- \*\*ŷ\*\* → predicted output  



\---



\## 🔁 Learning Rule (Core Idea)



The perceptron updates its weights only when it makes a mistake:



w = w + η · y · x  

b = b + η · y  



Where:

\- \*\*η (eta)\*\* = learning rate  

\- \*\*y\*\* = actual label  



👉 If prediction is correct → no update  

👉 If wrong → adjust weights toward correct class  



\---



\## 📊 Dataset Used (AND Gate)



| x1 | x2 | y |

|----|----|----|

| 0  | 0  | -1 |

| 0  | 1  | -1 |

| 1  | 0  | -1 |

| 1  | 1  | +1 |



\---



\## 🧪 Implementation



This project includes:



\- ✅ Perceptron implemented \*\*from scratch using NumPy\*\*

\- ✅ Comparison with \*\*scikit-learn implementation\*\*



\---



\## 📈 Final Model Learned



Weights: \[0.2, 0.1]  

Bias: -0.2  



Decision Boundary:

0.2x₁ + 0.1x₂ - 0.2 = 0  



\---



\## 💡 Key Insights



\- Perceptron learns by \*\*correcting mistakes\*\*

\- Works only for \*\*linearly separable data\*\*

\- Cannot solve problems like \*\*XOR\*\*



\---



\## 🚀 Next Step



👉 Explore why perceptron fails on XOR (Day 02)



\---



\## 📂 Files



\- `perceptron\_from\_scratch.py` → Custom implementation  

\- `sklearn\_comparison.py` → Validation using sklearn  

\- `notes.md` → Quick revision notes  



\---



\## 🎯 Goal of This Series



This is part of my \*\*ML Rewind Journey\*\*, where I revisit ML concepts from scratch and build strong fundamentals.



