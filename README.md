# Customer Financial Behavior & Risk Analysis

## Project Overview

This project analyzes customer financial behavior and identifies potential risk indicators using Python. The analysis focuses on transaction patterns, customer segmentation, account activity, anomaly detection, and financial risk assessment to support data-driven decision-making.

---

## Objectives

- Analyze customer transaction behavior across different account types.
- Compare debit and credit transaction trends over time.
- Identify dormant and high-performing accounts.
- Segment customers based on activity, balance, and transaction volume.
- Detect high-risk and suspicious accounts using statistical methods.
- Provide actionable business recommendations.

---

## Dataset Information

The dataset contains **800+ customer transactions** with features such as:

- Account ID
- Transaction Date
- Transaction Type
- Transaction Amount
- Account Balance
- Account Type
- Risk Score
- Credit Rating
- Region

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## Analysis Performed

### 1. Data Cleaning & Preprocessing
- Converted financial fields into numeric format.
- Validated and formatted date columns.
- Standardized account and transaction categories.

### 2. Descriptive Transaction Analysis
- Monthly and yearly credit/debit summaries.
- Net transaction volume analysis.
- Top and bottom performing accounts.
- Dormant account identification.

### 3. Customer Profile Building
- Activity-level segmentation (High, Medium, Low).
- Balance and transaction-volume segmentation.
- High-net inflow customer identification.
- High-frequency low-balance account profiling.

### 4. Financial Risk Identification
- Large withdrawal detection.
- Overdraft account analysis.
- Balance volatility calculation.
- Anomaly detection using IQR and Z-Score.
- Suspicious customer identification through composite risk scoring.

### 5. Exploratory Data Analysis (EDA)
- Transaction type distribution.
- Account type analysis.
- Regional transaction trends.
- Risk score distribution.
- Correlation analysis.
- Outlier visualization.

### 6. Hypothesis Testing
- T-Test for balance comparison across activity groups.
- ANOVA for customer segmentation validation.

---

## Key Findings

- Identified **26 suspicious accounts (13.5%)** using multi-factor risk scoring.
- Detected **48 high-volatility accounts (25%)**.
- Found **17 overdraft accounts** and **19 large-withdrawal accounts**.
- Debit transactions consistently exceeded credit transactions.
- Approximately **90% of accounts were dormant** based on inactivity analysis.
- Medium-activity customers represented the largest customer segment.

---

## Business Recommendations

- Monitor high-risk and suspicious accounts through automated alerts.
- Reduce dormancy using targeted customer engagement campaigns.
- Implement controls for frequent large withdrawals.
- Use customer segmentation for personalized marketing strategies.
- Continuously track volatility and overdraft indicators.

---

## Project Outcome

The project successfully delivered a comprehensive customer financial behavior and risk analysis framework. The insights generated can help financial institutions improve customer engagement, detect financial risks early, and support strategic decision-making.

---

## Repository Structure

```text
customer-financial-behavior-risk-analysis/
│
├── data/
├── notebooks/
├── reports/
├── images/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Author

**Nihal Mahto**

Aspiring Data Analyst | Python | SQL | Excel | Power BI
