# Model Summary – Customer Churn Prediction

Author: Anusha Durgam

## 📌 Problem
Classify whether a telecom customer will churn based on service usage and demographic data.

## 🧾 Dataset
- 7,000+ records, 20+ features
- Target: Churn (Yes/No)

---

## 🔍 Models Evaluated
- Logistic Regression
- Random Forest
- XGBoost
- SVM ✅ (Best Performance)

## ⚙️ Preprocessing
- One-hot encoding for categorical features
- StandardScaler for numerical
- Tenure Group bucketing for feature enhancement

---

## 🎯 Evaluation Metrics
- Accuracy
- F1-score
- Precision/Recall
- ROC-AUC
- Confusion Matrix

## ✅ Final Model
- **SVM**
- High accuracy & generalization
- Deployed via Streamlit

---

## 📊 Business Dashboard
- **Tool**: Power BI
- **File**: `churm analysis.pbix`
- **Insights**:
  - Churn breakdown by contract type
  - MonthlyCharges vs Tenure
  - Customer segmentation filters

---

## 🚀 Deployment
- Model served using Streamlit
- UI includes customer input + result
- Dashboard supports decision-making for stakeholders

---

## 🔚 Summary
This project delivers a complete ML pipeline with real-time prediction and executive-level reporting. The integration of Streamlit and Power BI enables both data science exploration and stakeholder engagement.
