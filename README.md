## Financial-Risk-Analysis-with-Python--JP-Morgan

# Overview
This repository is a complete Customer Financial Behavior and Risk Analysis Report using Python for data handling contains an end-to-end financial risk and customer behavior analysis based on transactional account data.This project clean and consolidate JP Morgan’ customer account data, uncover transaction insights, and help decision-makers align customer strategies with usage trends and financial risk indicators.

# Project Objectives
• Analysed customer transaction behaviour across multiple account types.
• Compare debit and credit transaction patterns.
• Detect dormant, inactive, or risky customer accounts.
• Perform customer segmentation using balance and transaction frequency.
• Conduct hypothesis testing to validate business assumptions.
• Provide actionable recommendations for risk management and customer engagement.

# Business Problem
Banks need to understand customer transaction behavior and identify early warning signs of financial risk. This project addresses the following questions:
How do credits and debits behave over time across accounts?
Which accounts show strong net inflow and which show heavy net outflow?
Which accounts show risky patterns such as large withdrawals, unstable balances, or anomalous transactions?
Does high transaction volume reliably indicate higher average balance?

# Dataset Summary
The dataset contains transaction-level records including:

Identifiers: TransactionID, CustomerID, AccountID
Categorical fields: AccountType, TransactionType, Product, Firm, Region, Manager
Numerical fields: TransactionAmount, AccountBalance, RiskScore, CreditRating, TenureMonths
Date field: TransactionDate
Transaction types observed include Deposit, Withdrawal, Payment, and Transfer.

# Tools & Skills Used
• Python
• Jupyter Notebook
• Data cleaning, transformation, and analysis
• Pandas & NumPy
• Data preprocessing, aggregation, and numerical analysis
• Matplotlib & Seaborn
• Data visualization and exploratory analysis
• MS Word
• Exploratory Data Analysis (EDA)
• Trend analysis, KPI calculation, and pattern identification

# Approach Summary
# 1. Data Cleaning and Preparation
The dataset was cleaned and standardized before analysis. Non-numeric values and special characters were removed from financial columns. Date columns were converted into proper datetime format to support monthly and yearly analysis. Account categories and transaction types were standardized to maintain consistency throughout the project. 
# 2. Descriptive Transaction Analysis 
Monthly and yearly summaries were created to analysed total credits, total debits, and overall transaction volume. Trend analysis showed how customer transaction behaviour changed over time. Accounts with the highest and lowest net inflows were identified to understand customer profitability and account performance. 
# 3. Customer Segmentation
Customers were grouped into High, Medium, and Low activity categories based on transaction frequency. Additional segmentation was performed using average balances and transaction volume. Special customer profiles were created for:
• High-net in-flow accounts 
• Negative or near-zero balance accounts
• High-frequency low-balance accounts
# 4. Financial Risk Identification
Risk analysis was performed to identify suspicious or irregular customer activity. Accounts with frequent large  withdrawals, overdrafts, or unstable balances were highlighted. Statistical methods such as standard deviation, z-score were used to detect unusual transaction behaviour and anomalies. 5. Visualization and Exploratory Data Analysis
Multiple visualizations were created to improve understanding of transaction patterns and customer behaviour. Charts such as line plots, bar charts, histograms, and heatmaps helped identify trends, correlations, and risk indicators within the dataset.
# 6. Hypothesis Testing Analysis
Statistical hypothesis testing techniques were used to validate assumptions and compare customer behaviour patterns.

# Key Insights
• High-frequency transaction accounts often maintained lower average balances.
• Some customer accounts showed irregular withdrawal patterns that may indicate financial risk.
• Transaction activity varied significantly across customer segments and account types.
• Statistical testing confirmed meaningful differences in operational and customer behaviour metrics. 
• Visual analysis revealed strong patterns between transaction volume and account stability.

# Recommendations
• Implement automated alerts for abnormal withdrawal behaviour and overdrafts.
• Develop personalized engagement strategies for dormant or inactive customers.
• Introduce risk scoring models for early fraud and anomaly detection. 
• Provide targeted financial products to high-value customer segments. 
• Monitor low-balance high-frequency accounts more closely to reduce financial risk exposure.
• Continue using statistical analysis and visualization dashboards for ongoing business monitoring.

# Conclusion
The project successfully demonstrated how Python can be used for financial transaction analysis, customer segmentation, and risk detection. By combining data cleaning, visualization, statistical testing, and meaningful business insights were generated. These findings can help financial institutions improve customer service, strengthen risk management practices, and support better decision-making.
