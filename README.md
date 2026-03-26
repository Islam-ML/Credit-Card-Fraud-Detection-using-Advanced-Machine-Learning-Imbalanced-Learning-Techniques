# 💳 Credit Card Fraud Detection
### Advanced Machine Learning Approach for Imbalanced Data Classification

**Author:** Islam Abdelrahim  
**Date:** March 2026  
**Type:** Binary Classification  

---

## 📖 Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques, with a strong focus on handling **highly imbalanced data**.

The workflow follows a complete end-to-end data science pipeline including:
- Data Analysis  
- Data Preprocessing  
- Feature Engineering  
- Model Training  
- Model Evaluation  

---

## 📊 Dataset
- Source: Kaggle - Credit Card Fraud Detection Dataset  
- Features: V1–V28 (anonymized), Time, Amount  
- Target: Class (0 = Non-Fraud, 1 = Fraud)  

### ⚠️ Class Imbalance
- Non-Fraud: ~99.8%  
- Fraud: ~0.2%  

---

## 🧰 Technologies & Libraries
- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  
- LightGBM  
- Imbalanced-learn (SMOTE)  

---

## 🔍 Project Workflow

### 1️⃣ Data Loading & Exploration
- Dataset inspection  
- Missing values check  
- Duplicate removal  

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Class distribution visualization  
- Transaction amount analysis  
- Time-based fraud trends  
- Correlation heatmap  

---

### 3️⃣ Data Preprocessing
- Feature scaling using `RobustScaler`  
- Train-test split with stratification  

---

### 4️⃣ Handling Imbalanced Data
- Applied **SMOTE (Synthetic Minority Oversampling Technique)**  

---

### 5️⃣ Feature Engineering & Selection
- Feature importance using **Mutual Information**  

---

### 6️⃣ Model Training
Trained and compared multiple models:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- LightGBM  

---

### 7️⃣ Model Evaluation
Models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  

Also included:
- ROC Curve  
- Precision-Recall Curve  
- Confusion Matrix  

---

## 🏆 Results
- Best model selected based on **F1-Score and ROC-AUC**
- Successfully handled extreme class imbalance
- Achieved strong fraud detection performance  

---

## 📈 Key Insights
- Handling imbalanced data is critical in real-world problems  
- Accuracy alone is misleading in fraud detection  
- Ensemble models outperform traditional models  

---


