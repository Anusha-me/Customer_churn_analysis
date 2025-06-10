# Model Summary – Customer Churn Analysis

Author: Anusha Durgam

## 🎯 Problem:
Predict whether a customer will churn based on demographic and service-related features.

## 🧪 Dataset:
- ~7,000+ entries
- 20+ features including service type, payment methods, and customer tenure
- Target: `Churn` (Yes=1, No=0)

---

## 📘 Models Tested:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

---

## ✅ Final Model: SVM (or replace with final used model)
- Accuracy: ~82%
- ROC-AUC: ~0.85
- Selected for high precision and generalization

---

## 📊 Feature Engineering:
- One-hot encoding for categorical features
- StandardScaler for numerical features
- Tenure bucketization (e.g., 1–12, 13–24, etc.)

---

## 📈 Evaluation Metrics:
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score
- ROC Curve and AUC

---

## 🚀 Deployment:
- Streamlit used for real-time prediction interface
- Power BI dashboard built for churn insights and executive reporting

## 💡 Final Takeaway:
Customer churn prediction enables proactive retention strategies. A well-tuned SVM/XGBoost model with clear visual feedback helps improve business decisions and customer satisfaction.
