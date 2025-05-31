# Customer Churn Analysis

This project analyzes real-world customer data from a telecom company to uncover why customers leave (churn) and builds a predictive model to identify those at risk. The goal is to help businesses reduce churn by understanding key behaviors and customer characteristics.

---

## Objectives

- Identify key drivers of customer churn using exploratory data analysis (EDA)
- Build and evaluate a predictive machine learning model
- Provide actionable recommendations to improve customer retention

---

## Tools & Technologies

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook
- Scikit-learn

---

## Key Insights

- Customers with **month-to-month contracts** had the highest churn rate
- Higher **monthly and total charges** were associated with increased churn
- Customers without **Tech Support** and/or **Online Security** were more likely to leave
- **Paperless billing** and **manual payment methods** are correlated with higher churn

---

## Model Performance

A **Random Forest Classifier** was trained on the encoded dataset:

- **Accuracy:** ~80%
- **Top Features:** `TotalCharges`, `Contract`, `TechSupport_Yes`, `OnlineSecurity_Yes`, `PaymentMethod_Electronic check`

---

## 📌 Business Recommendations

- Incentivize customers to switch to longer-term contracts
- Offer free trials or bundled packages for Tech Support and Online Security
- Promote auto-pay options over manual payment methods
- Launch onboarding campaigns for new customers (0–3 months tenure)

---

## 📂 Files

- `customer_churn_eda.ipynb`: Full notebook with EDA, modeling, and feature importance analysis
- `README.md`: Project overview and insights

---

## 📬 Contact

*Created by Jeily Antigua*  
Feel free to connect with me on [LinkedIn](www.linkedin.com/in/jeilyantigua) and check out more projects on [jeilyantigua.github.io](https://jeilyantigua.github.io)
