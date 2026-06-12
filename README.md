# Customer Churn Prediction

## Overview

Customer churn prediction is a crucial business problem that helps organizations identify customers who are likely to discontinue their services. This project develops a Machine Learning pipeline to predict customer churn using customer demographic and behavioral data.

The goal is to assist businesses in improving customer retention strategies by identifying at-risk customers before they leave.

---

## Problem Statement

Customer acquisition is significantly more expensive than customer retention. By accurately predicting churn, companies can:

- Reduce customer attrition
- Improve customer satisfaction
- Design targeted retention campaigns
- Increase long-term revenue

This project uses historical customer data to classify whether a customer is likely to churn.

---

## Dataset Features

The dataset contains customer-related information such as:

- Customer Age
- Account Balance
- Tenure
- Number of Products
- Credit Score
- Active Membership Status
- Geography
- Gender
- Estimated Salary

### Target Variable

- **Churn** (0 = No, 1 = Yes)

---

## Project Workflow

### 1. Data Preprocessing

- Handling missing values
- Encoding categorical variables
- Feature scaling
- Data cleaning

### 2. Exploratory Data Analysis (EDA)

- Churn distribution analysis
- Correlation analysis
- Customer segmentation
- Feature relationship visualization

### 3. Feature Engineering

- Creating meaningful predictive features
- Transforming categorical variables
- Selecting important features

### 4. Model Training

The following Machine Learning algorithms were explored:

- Logistic Regression
- Random Forest
- XGBoost

### 5. Model Evaluation

Performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

### 6. Model Serialization

The final trained model is saved using Pickle for future deployment and inference.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Pickle
- Jupyter Notebook

---

## Project Structure

```text
Customer_Churn_Prediction/
│
├── Analysis.ipynb
├── customer_data.csv
├── best_churn_pipeline.pkl
├── README.md
│
└── outputs/
```

---

## Results

The trained model successfully learns customer behavior patterns and predicts potential churners with strong classification performance.

These predictions can help businesses proactively engage customers and improve retention rates.

---

## Future Improvements

- Hyperparameter tuning
- Model deployment using Streamlit
- Real-time prediction dashboard
- Explainable AI using SHAP
- Automated retraining pipeline

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Feature engineering
- Exploratory Data Analysis
- Classification algorithms
- Model evaluation
- End-to-end Machine Learning workflow

---

## Author

**Tanu Shree**  
IIT (ISM) Dhanbad

GitHub: https://github.com/tanu99C
