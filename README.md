# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview
Customer churn refers to customers who stop using a company’s service.  
This project focuses on predicting whether a customer will churn using machine learning techniques so that businesses can take preventive actions.

-------------

## 🎯 Business Problem
Can we predict which customers are likely to churn so the company can reduce customer loss and improve retention?

------------

## 🧠 Type of Machine Learning
- Binary Classification
- Supervised Learning

Target Variable:
- `Churn`  
  - 0 → Customer did not churn  
  - 1 → Customer churned  

------------

## 📂 Dataset Description
The dataset contains **7044 customer records** with the following information:
- Customer demographics
- Contract details
- Billing and payment information
- Tenure and service usage

------------

## 🔧 Data Preprocessing Steps
- Converted `TotalCharges` column to numeric
- Handled missing values using median
- Dropped `customerID` as it has no predictive value
- Encoded categorical variables
- Created a new feature: `AvgMonthlySpend`
- Scaled numerical features

-----------------

## 📊 Exploratory Data Analysis (EDA)
Key observations:
- Month-to-month contract customers churn more
- New customers have higher churn risk
- High monthly charges increase churn probability
- Long-term customers are more loyal

--------------------

## 🤖 Models Used
1. Logistic Regression
2. Random Forest Classifier

--------------

## 📈 Model Performance

### Logistic Regression
- Accuracy: ~78.5%
- Better interpretability
- Chosen as final model due to business explainability

### Random Forest
- Accuracy: ~76%
- Performance similar to Logistic Regression
- Less interpretable

--------------------

## 🔍 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Special focus was given to **Recall for churn customers**, as missing a churn customer can lead to revenue loss.

---------------------

## 💡 Business Insights
- Encourage monthly users to switch to long-term contracts
- Focus retention strategies on first 3–6 months
- Offer discounts to high monthly charge customers
- Promote automatic payment methods
- Reward long-tenure customers

------------------

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- VS Code
- Git & GitHub

------------------------

## 🚀 Conclusion
This project demonstrates an end-to-end machine learning workflow including data cleaning, EDA, model building, evaluation, and business interpretation to reduce customer churn.

