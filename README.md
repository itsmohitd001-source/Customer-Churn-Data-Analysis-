# Customer-Churn-Data-Analysis-

>>Project Overview
This project analyses customer churn behaviour using a dataset containing 7K+ customer records and 21 features. The objective is to identify key factors driving customer churn.

>>Business Problem
Customer churn impacts revenue and profitability.
The goal of this analysis is to:
   --->Identify high-risk customer segments.
  
>>Tools & Technologies
Python
Pandas – Data Cleaning & Manipulation
NumPy – Numerical Analysis
Matplotlib & Seaborn – Data Visualization
Google Colab

>>Key Features:
-->Demographics (Gender, SeniorCitizen, Partner, Dependents)
-->Account Info (Tenure, Contract, Payment Method)
-->Services (InternetService, OnlineSecurity, TechSupport, StreamingTV, etc.)
-->Financials (MonthlyCharges, TotalCharges)


>>Data Cleaning & Preprocessing
-->Replaced blank values in TotalCharges and converted datatype to float.
-->Checked and confirmed 0 missing values and 0 duplicate records.
-->Converted SeniorCitizen from binary (0/1) to categorical (Yes/No) for better interpretability.
-->Validated unique customerID entries.

>>Exploratory Data Analysis (EDA)
-->Key Visualizations Performed:
-->Churn distribution analysis.
-->Gender vs Churn comparison.
-->Senior Citizen vs Churn behaviour.
-->Tenure distribution by churn.
-->Contract type vs churn.
-->Service-wise churn analysis using multi-plot categorical count plots.

>>Key Insights
-->Customers with month-to-month contracts show significantly higher churn rates.
-->Customers with low tenure (1–2 months) are more likely to churn.
-->Long-term contract customers demonstrate higher retention.
-->Certain service combinations (e.g., lack of OnlineSecurity or TechSupport) correlate with increased churn risk.

>> Business Recommendations
-->Promote long-term contracts with incentives to reduce churn.
-->Target new customers (low tenure) with onboarding engagement campaigns.

