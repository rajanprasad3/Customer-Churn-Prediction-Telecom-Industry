# 📊 Customer Churn Prediction – Telecom Industry

Predicting telecom customer churn using Machine Learning with Random Forest, SMOTE, and SHAP explainability.

---

## 🎯 Project Objective

Customer churn is a major challenge in the telecom industry. This project aims to:

- Predict customers likely to churn
- Handle class imbalance effectively
- Identify key churn drivers
- Provide actionable business insights to reduce churn

---

## 📁 Dataset

- **Source:** Kaggle – Telco Customer Churn Dataset  
- **Records:** 7,000+ customers  
- **Features:** 20+ customer attributes  
- **Target Variable:** `Churn (Yes/No)`

Features include:
- Contract type
- Tenure
- Internet service
- Monthly charges
- Total charges
- Payment method
- Demographic details

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- SHAP
- Matplotlib
- Seaborn

---

## 🔬 Project Workflow

### 1️⃣ Data Preprocessing
- Removed unnecessary columns
- Handled missing values
- Converted categorical variables using one-hot encoding
- Transformed target variable into binary format

### 2️⃣ Feature Engineering
- Engineered 12+ predictive features
- Encoded service types and contract structures

### 3️⃣ Handling Class Imbalance
- Applied **SMOTE** to balance dataset
- Improved minority class recall significantly

### 4️⃣ Model Building
- Random Forest Classifier
- Hyperparameter tuning using GridSearchCV
- 5-fold Cross-Validation

---

## 📈 Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | ~87% |
| ROC-AUC | ~0.91 |
| Recall Improvement | +31% (after SMOTE) |

---

## 📊 Model Evaluation Visualizations

- Confusion Matrix
- ROC Curve
- Feature Importance Plot
- SHAP Summary Plot

---

## 🔍 Top 5 Churn Drivers (SHAP Analysis)

- Month-to-month contract
- Low tenure
- High monthly charges
- Fiber optic internet service
- Electronic check payment method

---

## 💡 Business Insights

- Customers on month-to-month contracts are most likely to churn.
- New customers (low tenure) have higher churn probability.
- High monthly charges increase churn risk.
- Targeted retention strategies can reduce churn by ~22%.

### Recommended Actions:
- Offer long-term contract discounts
- Provide loyalty benefits after 12 months
- Early engagement campaigns for new customers
- Personalized offers for high-risk segments

---

## 🚀 Future Improvements

- Deploy model using Streamlit
- Compare with XGBoost & Logistic Regression
- Build churn monitoring dashboard
- Convert into production-ready ML pipeline

---

## 📂 Project Structure

```
customer-churn-telecom/
│
├── data/
├── notebooks/
├── src/
├── requirements.txt
└── README.md
```

---

## 📌 Conclusion

This project demonstrates an end-to-end machine learning workflow including data preprocessing, imbalance handling, model optimization, and business-focused explainability. The final model provides reliable churn predictions and actionable retention strategies.

---

⭐ If you found this project helpful, consider giving it a star!
