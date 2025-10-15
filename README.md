# 📞 Telco Customer Churn Prediction & Analysis

An end-to-end data analytics and machine learning project to predict customer churn for a telecom company using Python and Power BI.  
The goal is to identify customers likely to discontinue services and provide actionable retention insights.

---

## 🚀 Project Overview
This project analyzes 7,000+ customer records to understand churn behavior and build a predictive model.  
It combines **data cleaning**, **exploratory data analysis (EDA)**, **machine learning**, and **dashboard visualization**.

---

## 🧩 Features
- 🧹 **Data Cleaning & Preprocessing:** Handled missing values, converted datatypes, and encoded categorical variables.  
- 📊 **EDA & Visualization:** Churn rate by contract type, payment method, internet service, and tenure groups.  
- 🤖 **Machine Learning Models:** Logistic Regression & Random Forest achieving ~80% accuracy and 0.75 ROC-AUC.  
- 🔍 **Feature Importance Analysis:** Identified key churn drivers such as low tenure, high monthly charges, and fiber optic plans.  
- 🧮 **PCA & Correlation Study:** Reduced dimensionality and visualized key relationships.  
- ⚡ **Interactive Power BI Dashboard:** Displays churn KPIs, demographics, and service patterns.  
- 🔮 **Single-Customer Prediction:** Predict churn probability for individual customer inputs.

---

## 🛠️ Tech Stack
**Languages & Libraries:**  
`Python`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`  

**Visualization:**  
`Power BI`, `matplotlib`, `seaborn`

---

## 🧱 Project Workflow
1. Data Cleaning (pandas)
2. EDA & Visualization
3. Feature Engineering & Encoding
4. Model Training (Logistic Regression & Random Forest)
5. Evaluation (Accuracy, F1, ROC-AUC)
6. Power BI Dashboard Design
7. Model Saving & Single Prediction Demo

---

## 📊 Power BI Dashboard
The Power BI dashboard highlights:
- Overall churn percentage  
- Churn rate by contract type and payment method  
- Tenure vs Churn correlation  
- Key churn drivers (identified from ML model)  

---

## 🧠 Results
| Metric | Logistic Regression | Random Forest |
|:-------:|:-------------------:|:--------------:|
| Accuracy | 80% | 78% |
| F1 Score | 0.58 | 0.52 |
| ROC-AUC | 0.71 | 0.68 |

---

## 🧰 How to Run
```bash
pip install -r requirements.txt
python churn_main.py
