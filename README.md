# 📌 Credit Risk Prediction Using Machine Learning

A machine learning project designed to classify customers into different **credit risk categories** based on financial, demographic, and behavioral attributes. This end-to-end workflow includes **data cleaning, feature engineering, EDA, model training, evaluation, and model comparison**.

---

## 📊 Project Overview

Financial institutions face ongoing challenges in identifying customers who may default on loans.  
This project builds a robust machine learning classification system to **predict credit risk**, helping organizations:

- Strengthen loan approval decisions  
- Reduce default rates  
- Improve customer credit assessment processes  

---

## 🚀 Key Features

- End-to-end ML pipeline  
- Data preprocessing & feature engineering  
- Exploratory Data Analysis (EDA)  
- Training & comparing multiple ML models  
- Visualization of performance metrics  
- Business-focused insights  

---

## 📁 Dataset

The dataset includes:

- Financial behavior metrics  
- Demographic attributes  
- Credit & repayment history  

**Target Variable:** Credit risk category (0, 1, 2, 3)

---

## 🧠 Machine Learning Models Used

Models evaluated in this project:

- Random Forest  
- XGBoost  
- Support Vector Classifier (SVC)  
- Logistic Regression  
- LightGBM  

---

## 🥇 Best Model (Overall)

### **Random Forest**
- **Accuracy:** 0.7633  
- Showed the most balanced and stable results across all classes  
- Performed well in detecting high-risk categories  

---

## 🧪 XGBoost Model Performance


### **Classification Report**

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|---------|----------|----------|
| 0 | 0.78 | 0.95 | 0.86 | 1103 |
| 1 | 0.28 | 0.03 | 0.05 | 1075 |
| 2 | 0.76 | 0.95 | 0.84 | 1099 |
| 3 | 0.77 | 0.94 | 0.85 | 2102 |

**Overall Accuracy:** 0.76  
**Macro Avg F1:** 0.65  
**Weighted Avg F1:** 0.69  

---

## 📈 Model Comparison

| Model | Accuracy | Precision | Recall | F1-score | AUC-ROC |
|-------|----------|------------|---------|-----------|-----------|
| Random Forest | 0.760736 | 0.635512 | 0.716747 | 0.654093 | 0.839587 |
| **XGBoost** | **0.762595** | **0.647733** | **0.717044** | **0.649590** | **0.837982** |
| SVC | 0.743075 | 0.556338 | 0.699196 | 0.619589 | 0.828227 |
| Logistic Regression | 0.699015 | 0.591650 | 0.658374 | 0.608291 | 0.821960 |
| LightGBM | 0.761294 | 0.633522 | 0.714703 | 0.640191 | 0.835305 |

---

## 📉 Business Impact

This credit risk prediction system can help banks and financial institutions:

- Identify high-risk customers early  
- Reduce loan default probability  
- Strengthen portfolio risk management  
- Improve credit scoring decision workflow  
- Prioritize customers for further manual review  

---

## 🛠️ Tech Stack

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **XGBoost**
- **LightGBM**
- **Jupyter Notebook**

---

## 📎 Project Files

- `Credit_Risk_Report.pdf` — Complete report  
- `.ipynb` Notebook — Full ML pipeline including preprocessing & model comparison  

---

## 👤 Author

**Zubayer Hasan**  
Data Analyst | ML Enthusiast  
Contact for collaboration or feedback.

---

