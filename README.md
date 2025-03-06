<h1>Customer Churn Analysis</h1>

<h2>Project Overview</h2>

This project analyzes customer churn behavior using a telecom dataset. The goal is to extract insights, identify key factors influencing churn, and provide actionable business recommendations.

<h2>Dataset</h2>

Source: Telecom customer dataset (CSV file)

Description: Contains customer demographic, service usage, and billing details, with a churn label indicating whether a customer left the service.

<h2>Steps in the Analysis</h2>

<h3>1. Data Cleaning</h3>

<li>Handled missing values (none in this dataset)</li>

<li>Converted categorical variables using One-Hot Encoding</li>

<li>Addressed skewness in numerical features</li>

<h3>2. Exploratory Data Analysis (EDA)</h3>

<li>Univariate Analysis: Distribution of key variables (MonthlyCharges, Tenure, etc.)</li>

<li>Bivariate Analysis: Relationship between churn and features (e.g., MonthlyCharges vs. Churn)</li>

<li>Multivariate Analysis: Heatmap and correlation studies</li>

<h3>3. Feature Engineering</h3>

<li>Created TotalMonthlySpend (MonthlyCharges × Tenure)</li>

<li>Derived AutoPay feature from PaymentMethod</li>

<li>Segmented customers based on contract types</li>

<h2>Key Insights</h2>

<li>High Monthly Charges increase churn likelihood.</li>

<li>New customers (tenure < 12 months) churn more often.</li>

<li>AutoPay users have lower churn rates.</li>

<li>Month-to-month contracts have the highest churn.</li>

<li>Churn is present in both high and low spenders (indicating dissatisfaction at both ends).</li>



<h2>How to Run the Code</h2>

Install required libraries:

`pip install pandas numpy matplotlib seaborn ydata-profiling`

Run the Python script or Jupyter Notebook step by step:

1. Load the dataset

2. Perform Data Cleaning & Preprocessing

3. Execute EDA and Feature Engineering

4. Analyze insights and interpret results

5. Visualizations and results will be displayed accordingly.
