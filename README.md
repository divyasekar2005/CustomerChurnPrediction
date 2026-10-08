# Customer Churn Prediction using KNIME - Decision Tree

## 📌 Project Objective
To predict whether a customer will churn (Yes/No) based on customer details like tenure, contract type, monthly charges, support calls, and internet services using Decision Tree in KNIME.

## 📊 Dataset Used
File: `KNIME_Decision_Tree_Customer_Churn.csv`

- **Total Records:** Customer transaction data
- **Key Features:** Age, Tenure_Months, Monthly_Income, Monthly_Charges, Support_Calls, Contract, Payment_Method, Internet_Service, Online_Security, Tech_Support
- **Target Variable:** Churn (Yes / No)

## ⚙️ Workflow Overview (KNIME)
1.  **Data Import:** CSV Reader to load customer data
2.  **Data Transformation:** Rule Engine used to create Customer Category
    - Tenure < 12 months → New Customer
    - Tenure ≥ 12 months → Existing Customer
3.  **Data Partitioning:**
