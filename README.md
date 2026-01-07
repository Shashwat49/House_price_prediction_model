# House Price Prediction Model
 * Linear Regression from Scratch (Python)

This project implements **Linear Regression from scratch** using Python and NumPy, without relying on high-level machine learning libraries like scikit-learn.

The goal of this notebook is to understand the **mathematics and intuition behind gradient descent**, cost functions, and learning rate tuning.

---

## 📌 Problem Statement
Given a dataset with input feature(s) `x` and target values `y`, we aim to learn the parameters:

- **w** (weight)
- **b** (bias)

such that the linear model:

ŷ = wx + b  

best fits the data by minimizing the **Mean Squared Error (MSE)** cost function.

---

## 🧠 Concepts Covered
- Linear regression hypothesis function
- Cost function (Mean Squared Error)
- Gradient descent optimization
- Partial derivatives of the cost function
- Learning rate (α) selection
- Convergence vs divergence in gradient descent

---

## ⚙️ Implementation Details
- Model implemented **from scratch**
- No ML libraries used for training
- Cost vs iterations plotted for visualization

---

## 📊 Results
- Gradient descent successfully converges after feature scaling
- Cost decreases monotonically with a suitable learning rate
- Learned parameters minimize the cost function

---

## 🛠️ Tech Stack
- Python
- NumPy
- Matplotlib
- Jupyter Notebook
