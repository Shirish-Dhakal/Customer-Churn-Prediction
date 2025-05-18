# 🔄 Customer Churn Prediction

This project aims to predict customer churn using machine learning, enabling businesses to proactively retain customers by identifying those at risk of leaving. The pipeline includes **data cleaning**, **exploratory analysis**, and model building using several algorithms, with **XGBoost** selected as the final model.

---

## 📌 Project Highlights

- Performed thorough **data cleaning**, handling missing values and encoding categorical features.
- Conducted **EDA** to understand churn patterns and feature distributions.
- Trained multiple models including Logistic Regression, Random Forest, and XGBoost.
- Selected **XGBoost** based on its superior performance across metrics.
- Achieved **99.68% accuracy**, **99.7% precision**, **98.8% recall**, and **99.2% F1-score**.
- Used a **confusion matrix** and model probability analysis for validation.
- Provided business insights and actionable recommendations based on predictions.

---

## 📊 Exploratory Data Analysis (EDA)

- Analyzed churn distribution across demographics and usage patterns.
- Visualized key features such as login frequency, spending, and recency.
- Identified correlations and removed redundant or low-importance variables.

---

## 🧹 Data Cleaning

- Removed duplicate and inconsistent records.
- Imputed missing values using statistical methods.
- Converted categorical variables using one-hot encoding.
- Normalized continuous variables for models like Logistic Regression.

---


## 📊 Model Performance (XGBoost)

| Metric     | Value     |
|------------|-----------|
| Accuracy   | 99.68%    |
| Precision  | 99.7%     |
| Recall     | 98.8%     |
| F1 Score   | 99.2%     |

---

## 💼 Business Applications

- 🎯 **Targeted Retention** – Intervene early for at-risk customers.
- 📞 **Customer Support Prioritization** – Focus on high-risk profiles.
- 💰 **CLV-Based Segmentation** – Combine risk scores with value tiers.
- 📉 **Churn Insights** – Identify trends driving attrition and refine service.

---

## 🚀 Potential Improvements

- Enhanced **feature engineering** (e.g., session trends, time-based patterns)
- Hyperparameter tuning using **Grid Search** or **Bayesian Optimization**
- **Model explainability** using SHAP for transparency
- **Ensemble blending** with Logistic Regression, XGBoost, and RF

---

## 🛠️ Tools & Libraries

- Python (Jupyter Notebook)
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost

---
