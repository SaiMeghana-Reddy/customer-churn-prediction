# Customer Churn Prediction📊

## Project Overview
This project focuses on predicting customer churn in a telecom company using machine learning techniques. The goal is to identify customers who are likely to leave the service so that retention strategies can be applied.

---

## Problem Statement
Customer churn is a major challenge for telecom businesses. By predicting churn, companies can take proactive measures to retain customers and reduce revenue loss.

---

## Dataset
- Telco Customer Churn Dataset
- Contains customer demographics, services, and account information

🔗 Dataset: [Download Dataset](./Telco_Customer_Churn_Dataset.csv)

---

## Project Workflow

1. Data Loading & Exploration  
2. Data Cleaning & Preprocessing  
3. Categorical Encoding  
4. Train-Test Split (80-20)  
5. Model Training (Logistic Regression)  
6. Model Evaluation  

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## Model Performance

| Metric      | Score |
|------------|------|
| Accuracy    | 82% |
| Precision   | 0.69 (Churn) |
| Recall      | 0.60 (Churn) |
| F1-Score    | 0.64 |

---

## Key Insights

- Customers with **month-to-month contracts** are more likely to churn  
- Higher **monthly charges** increase churn probability  
- Lack of services like **TechSupport** and **OnlineSecurity** leads to higher churn  

---

## How to Run

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt
