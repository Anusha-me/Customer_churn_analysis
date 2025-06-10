# Customer Churn Analysis and Prediction

This project aims to predict customer churn using a combination of machine learning models and exploratory data analysis. It includes model training, evaluation, Streamlit-based deployment, and Power BI dashboard integration.

## 📊 Dataset
- Source: `WA_Fn-UseC_-Telco-Customer-Churn.csv` & `tel_churn.csv`
- Size: ~7,000+ customer records
- Target: `Churn` (Yes/No)

## 🧠 Features Covered
- Demographics (gender, SeniorCitizen, Partner, Dependents)
- Account info (tenure, Contract, PaperlessBilling, PaymentMethod)
- Service details (InternetService, OnlineSecurity, TechSupport, etc.)
- MonthlyCharges, TotalCharges

---

## 🔍 Project Components
- `Churn Analysis - EDA.ipynb`: Exploratory data analysis, visual insights
- `Churn Analysis - Model Building.ipynb`: Preprocessing, training ML models
- `prediction.py`: Streamlit app for real-time prediction
- `Customer Churn Knowledge.py`: Educational Streamlit app
- `model.sav`: Trained classification model (e.g., SVM or Logistic Regression)
- `churm analysis.pbix`: Power BI report for business insights
- `.csv files`: Raw and cleaned datasets

---

## 🛠️ How to Run

### 1. Install dependencies:
```bash
pip install -r requirements.txt
