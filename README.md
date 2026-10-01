# 📈 Linear Regression From Scratch

<p align="center">
  Implementing Linear Regression and Gradient Descent from scratch to understand the fundamentals behind machine learning algorithms.
</p>

<p align="center">
  🧠 Machine Learning Fundamentals &nbsp; • &nbsp; 📐 Mathematics &nbsp; • &nbsp; 🐍 Python & NumPy
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
</p>

---

## 📌 Overview

This project implements **Linear Regression from scratch** to understand how the algorithm works internally instead of relying entirely on pre-built machine learning libraries.

The project focuses on the mathematical concepts behind regression and optimization, including:

- Linear Regression
- Cost Function
- Gradient Descent
- Model Parameters
- Predictions
- Batch Gradient Descent

---

## 🧠 Concepts Covered

### 📐 Linear Regression

The model learns a relationship between input features and a continuous target variable.

The basic equation is:

```text
ŷ = β₀ + β₁x
```

Where:

- `ŷ` = predicted value
- `β₀` = intercept
- `β₁` = coefficient
- `x` = input feature

---

### 📉 Cost Function

The model uses **Mean Squared Error (MSE)** to measure prediction error.

```text
MSE = (1/n) Σ(y - ŷ)²
```

The objective is to minimize this error.

---

### ⚙️ Gradient Descent

Gradient Descent is used to iteratively update the model parameters and minimize the cost function.

```text
parameter = parameter - learning_rate × gradient
```

The process continues until the model converges toward a minimum cost.

---

## 🔄 Workflow

```text
Input Data
    ↓
Initialize Parameters
    ↓
Make Predictions
    ↓
Calculate Cost
    ↓
Calculate Gradients
    ↓
Update Parameters
    ↓
Repeat
    ↓
Final Model
```

---

## 📚 Implementations

The project contains Jupyter notebooks covering different stages of the implementation.

```text
Linear Regression
      ↓
Gradient Descent
      ↓
Batch Gradient Descent
      ↓
Model Evaluation
```

---

## 📂 Project Structure

```text
linear-regression-from-scratch/
│
├── 📁 notebooks/
│   ├── Linear Regression notebooks
│   └── Gradient Descent notebooks
│
├── 📄 README.md
├── 📄 requirements.txt
└── 📄 .gitignore
```

---

## 🛠️ Tech Stack

- Python
- NumPy
- Jupyter Notebook
- Matplotlib
- Scikit-learn for comparison and evaluation

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/AnkanXcoder/linear-regression-from-scratch.git
```

### 2. Navigate to the project

```bash
cd linear-regression-from-scratch
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebooks

Open the notebooks inside the `notebooks/` directory using:

- Jupyter Notebook
- JupyterLab
- VS Code
- Google Colab

---

## 🧠 What I Learned

Through this project, I practiced:

- Understanding Linear Regression mathematically
- Implementing a model without relying on `sklearn.linear_model`
- Understanding model parameters
- Calculating prediction error
- Implementing Mean Squared Error
- Understanding gradients
- Implementing Gradient Descent
- Implementing Batch Gradient Descent
- Understanding the effect of learning rate
- Understanding model convergence
- Comparing a custom implementation with standard ML libraries

---

## 🎯 Project Goal

The main goal of this project is to understand **what happens inside a machine learning algorithm** rather than treating it as a black box.

Implementing the algorithm manually provides a stronger understanding of:

```text
Mathematics
    ↓
Optimization
    ↓
Algorithm
    ↓
Implementation
    ↓
Machine Learning Model
```

---

## 🔮 Future Improvements

- [ ] Add Multiple Linear Regression
- [ ] Add feature scaling
- [ ] Add R² score from scratch
- [ ] Add visualization of the cost function
- [ ] Add learning-rate experiments
- [ ] Add convergence visualization
- [ ] Add comparison with Scikit-learn
- [ ] Add regularization from scratch
- [ ] Add Ridge Regression
- [ ] Add Lasso Regression

---

## 👨‍💻 Author

### Ankan Sen

**B.Tech Computer Science & Engineering Student**

Interested in:

- 📊 Data Science
- 🤖 Machine Learning
- 📈 Data Analytics
- 🐍 Python
- 🗄️ SQL

<p align="center">
  <a href="https://github.com/AnkanXcoder">
    <img src="https://img.shields.io/badge/GitHub-AnkanXcoder-black?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/ankan-sen-2725b9325">
    <img src="https://img.shields.io/badge/LinkedIn-Ankan%20Sen-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
</p>

---

<p align="center">
  Built with 🐍 Python • 🧠 Machine Learning • 📐 Mathematics
</p>
