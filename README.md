# 🏦 Bank Customer Churn Prediction using ANN

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Keras](https://img.shields.io/badge/Keras-Model-red?logo=keras)
![NumPy](https://img.shields.io/badge/NumPy-Array-blue?logo=numpy)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

### 📌 Overview
Built an artificial neural network (ANN) to predict customer churn using the *Churn for Bank Customers* dataset. The project focuses on preprocessing, optimizer tuning, and model generalization to improve classification performance.

---

### 🚀 Features
- Preprocessing pipeline with feature selection and StandardScaler  
- ANN architecture with multiple dense layers, dropout, and early stopping  
- Experimented with optimizers (SGD, RMSProp, Adagrad, Adam, Nadam) to select best model  
- Evaluation using accuracy and confusion matrix

---

### 🗂️ Dataset
- **Source:** Kaggle - Churn for Bank Customers  
- **Records:** ~10,000 rows  
- **Format:** CSV - cleaned and encoded to numeric features for model input

---

### 🛠️ Tech Stack
`Python` • `Keras` • `scikit-learn` • `Pandas` • `NumPy` • `Matplotlib`

---

### 📊 Results
- Best performing optimizer: **Nadam** → **86.93% accuracy** on test set  
- Used dropout and early stopping to reduce overfitting and improve generalization

---

### 🧩 How to Run Locally
```bash
git clone https://github.com/<your>/Bank-Client-Retention-Prediction
cd Bank-Client-Retention-Prediction
pip install -r requirements.txt
# Run training script or notebook
python train_model.py
