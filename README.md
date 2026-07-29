# project_dashboard
# HR Analytics - Employee Attrition Prediction

## Overview

This project analyzes employee attrition using machine learning and data visualization. The objective is to identify the major factors influencing employee resignation and build predictive models to estimate the likelihood of employee attrition.

The project combines Exploratory Data Analysis (EDA), classification models, SHAP explainability, and an interactive Power BI dashboard.

---

## Objectives

- Analyze employee attrition trends
- Identify factors contributing to employee resignation
- Build predictive classification models
- Explain model predictions using SHAP values
- Develop an interactive Power BI dashboard

---

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- SHAP
- Power BI

---

## Dataset

IBM HR Analytics Employee Attrition Dataset

Features include:

- Age
- Department
- Job Role
- Monthly Income
- Business Travel
- Overtime
- Job Satisfaction
- Years at Company
- Attrition

---

## Exploratory Data Analysis

The following analyses were performed:

- Overall Attrition Distribution
- Attrition by Department
- Attrition by Job Role
- Monthly Income vs Attrition
- Attrition by Overtime

---

## Machine Learning Models

Two classification models were implemented:

### Logistic Regression

- Standardized features
- Balanced class weights
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC-AUC

### Decision Tree Classifier

- Max Depth = 6
- Balanced class weights
- Performance comparison with Logistic Regression

---

## Model Explainability

SHAP (SHapley Additive Explanations) was used to explain feature importance and understand model predictions.

---

## Power BI Dashboard

The dashboard includes:

- Total Employees
- Attrition Count
- Attrition Rate
- Average Monthly Income
- Attrition by Department
- Attrition by Job Role
- Attrition by Salary Band
- Attrition by Overtime
- Attrition by Business Travel
- Gender Distribution of Employees Who Left

Interactive slicers:

- Department
- Gender
- Job Role
- Marital Status
- Business Travel

---

## Project Structure

```
HR-Analytics-Employee-Attrition/
│
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── notebooks/
│   └── HR_Analytics.ipynb
│
├── dashboard/
│   └── HR_Analytics_Dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

## Results

The analysis identified several important factors associated with employee attrition, including:

- Overtime
- Monthly Income
- Job Role
- Department
- Business Travel

The Power BI dashboard enables interactive exploration of these insights.

---

## Future Improvements

- Hyperparameter tuning
- Random Forest and XGBoost models
- Deployment using Streamlit
- Real-time HR dashboard
- Automated prediction API

---

## Author

Your Name
