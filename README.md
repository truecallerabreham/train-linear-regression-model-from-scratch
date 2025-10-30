# train-linear-regression-model-from-scratch
A simple machine learning project implementing Linear Regression from scratch using Python
# Linear Regression from Scratch (Using the Gram Matrix / Normal Equation)

This project demonstrates how to implement a **Linear Regression model from scratch** using the **Normal Equation (Gram Matrix method)** instead of gradient descent.  
It was developed in **Google Colab** as part of my learning journey in Machine Learning fundamentals.

---

## 🧠 Project Overview

The goal of this project is to understand how Linear Regression can be solved analytically using linear algebra — without relying on machine learning libraries.

The key mathematical idea is:

\[
w = (X^T X)^{-1} X^T y
\]

where  
- **X** → the feature matrix  
- **y** → the target vector  
- **w** → the optimal weight vector minimizing the cost function

This method provides the exact solution for the model parameters when \( X^T X \) is invertible.

---

## ⚙️ Steps Implemented

1. Imported and prepared the dataset  
2. Added bias term to the feature matrix  
3. Computed the **Gram Matrix (XᵀX)**  
4. Calculated the **inverse** of the Gram Matrix  
5. Computed weights using the Normal Equation  
6. Predicted the target values  
7. Visualized the regression line and performance

---

## 🚀 Technologies Used

- Python  
- NumPy  
- Matplotlib  
- Google Colab

---

## 📈 Results

- Derived weights analytically using the Normal Equation  
- Verified predictions and visualized the regression line  
- Gained a clear understanding of how Linear Regression works internally  

---

## 📓 Notebook

You can view or run the notebook directly on Google Colab:

👉 [Op]()
