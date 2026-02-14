# 📊 Linear Regression — Predicting Revenue

A Machine Learning project that uses **Simple Linear Regression** to predict revenue based on historical data.

This project demonstrates the complete ML workflow — from data preprocessing to model training and evaluation — using Python and scikit-learn.

---

## 🚀 Project Objective

To build a regression model that learns the relationship between an input feature and revenue, and then predicts future revenue values.

---

## 🧠 What is Linear Regression?

Linear Regression is a **Supervised Learning algorithm** used to predict continuous numerical values.

Mathematical model:

Y = β₀ + β₁X

Where:
- Y → Predicted Revenue  
- X → Input Feature  
- β₀ → Intercept  
- β₁ → Slope (coefficient)  

The model minimizes error using **Mean Squared Error (MSE)**.

---


### 1️⃣ Import Libraries
- pandas  
- numpy  
- matplotlib  
- scikit-learn  

---
### 2️⃣ Load Dataset
Read CSV file and inspect data.

### 3️⃣ Exploratory Data Analysis (EDA)
- Check data distribution  
- Visualize feature vs revenue  

### 4️⃣ Train/Test Split
Split dataset into training and testing sets.

### 5️⃣ Model Training

from sklearn.linear_model import LinearRegression
### 6️⃣ Model Evaluation
Evaluate performance using:

R² Score

Mean Squared Error

---

### 7️⃣ Prediction
Predict revenue for new input values.

### 📦 Requirements
Install dependencies:

pip install pandas numpy matplotlib scikit-learn
### 💡 Key Learnings
Understanding Linear Regression fundamentals

Model training & evaluation

Data visualization

End-to-end ML pipeline implementation
