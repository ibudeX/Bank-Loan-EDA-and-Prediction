# 🏦 Bank Loan Default Prediction

## 📘 Project Overview
This project focuses on predicting the likelihood of **loan default** based on customer financial, demographic, and behavioral data.  
By applying **data preprocessing, exploratory data analysis (EDA), feature engineering**, and **machine learning modeling**, the goal is to assist financial institutions in identifying **high-risk applicants** and improving lending decisions.

---

## 📊 Dataset Description
The dataset contains customer loan application records, including features such as:
- **Customer ID**
- **Gender, Marital Status, Dependents**
- **Education & Employment Type**
- **Applicant & Coapplicant Income**
- **Loan Amount & Loan Term**
- **Credit History**
- **Property Area**
- **Loan Status** (Target Variable: Approved / Not Approved)

---

## ⚙️ Data Preprocessing
Steps performed before model training:
1. **Handling missing values** using median/mode imputation  
2. **Encoding categorical variables** (Label Encoding & One-Hot Encoding)  
3. **Feature scaling** for numerical variables  
4. **Outlier detection** using IQR method  
5. **Splitting** data into training and testing sets (80/20 ratio)

---

## 🔍 Exploratory Data Analysis (EDA)
The EDA phase explored data patterns and variable relationships to understand loan approval behavior.  

Key analyses include:
- Distribution of **loan approval rate**  
- Relationship between **income and loan amount**  
- Correlation between **credit history** and loan status  
- Effect of **education and property area** on approval rates  
- Income comparison between **defaulters vs non-defaulters**


---

## 💡 Insights
- Applicants with a **positive credit history (1)** are significantly more likely to get loan approval.  
- **Self-employed** individuals have slightly lower approval rates compared to salaried applicants.  
- **Higher applicant income** generally leads to a **higher chance of approval**, especially when coupled with smaller loan amounts.  
- **Urban applicants** show slightly better approval odds than rural ones, likely due to stable employment opportunities.  
- **Loan term** and **education level** have a moderate effect on default likelihood.

---

## 🧭 Recommendations
- Prioritize applicants with **good credit history** for fast-track approval.  
- Introduce **credit counseling** or **loan education programs** for low-credit applicants.  
- Implement **AI-based income verification** to reduce fraudulent approvals.  
- Offer **tiered loan interest rates** based on risk scores derived from model predictions.  
- Continuously **retrain the model** using new data for better accuracy.

---

## 🧠 Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn)
- **Matplotlib** & **Seaborn** for visualizations  
- **Jupyter Notebook** for development  
- **LabelEncoder / StandardScaler** for preprocessing  
- **Logistic Regression, Random Forest, XGBoost** for prediction modeling  

---

## 📊 Model Evaluation
| Model | Accuracy | Precision | Recall | F1 Score |
|--------|-----------|------------|----------|-----------|
| Logistic Regression | 82% | 79% | 83% | 81% |
| Random Forest | 86% | 84% | 88% | 86% |
| XGBoost | **88%** | **87%** | **89%** | **88%** |

> XGBoost achieved the highest performance and was selected as the final model.

---

## 🚀 Future Improvements
- Include **customer behavioral data** (e.g., repayment history, spending patterns).  
- Integrate **SHAP or LIME** for explainable AI (model interpretability).  
- Deploy model via **Flask API** or **Streamlit dashboard**.  
- Automate daily model retraining pipeline.

---


---

