# BANK-FRAUD-ANALYSIS
# 💳 Banking Fraud Analytics Dashboard

A Power BI dashboard designed to analyze credit card fraud transactions, identify high-risk patterns, and support fraud investigation. This project demonstrates data visualization, KPI tracking, DAX calculations, and interactive reporting using a synthetic banking dataset.

---

## 📌 Project Overview

Financial institutions process thousands of transactions every day. Detecting fraudulent activity quickly is essential to reduce financial losses and improve customer security.

This dashboard provides insights into:
- Fraud transaction trends
- High-risk merchant categories
- Transaction amount analysis
- Device trust analysis
- Transaction velocity monitoring
- Fraud investigation

---

## 🎯 Objectives

- Monitor overall fraud performance
- Identify suspicious transaction patterns
- Analyze fraud by merchant category
- Evaluate device trust score impact
- Investigate high-risk transactions
- Build an interactive Power BI dashboard for business users

---

## 🛠 Tools Used

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel (CSV Dataset)

---

## 📂 Dataset

Dataset Name:
**credit_card_fraud_10k.csv**

### Columns

- transaction_id
- amount
- cardholder_age
- device_trust_score
- foreign_transaction
- is_fraud
- location_mismatch
- merchant_category
- transaction_hour
- velocity_last_24h

---

# 📊 Dashboard Pages

## Dashboard 1 — Executive Overview

### KPIs
- Total Transactions
- Fraud Transactions
- Fraud Rate
- Total Fraud Amount

### Charts
- Fraud vs Genuine Transactions
- Fraud by Merchant Category
- Fraud by Transaction Hour
- Fraud by Foreign Transactions

---

## Dashboard 2 — Fraud Risk Analysis

### KPIs
- Average Transaction Amount
- Average Device Trust Score
- Foreign Fraud Transactions
- Location Mismatch Transactions

### Charts
- Fraud by Location Mismatch
- Fraud by Foreign Transactions
- Device Trust Score Distribution
- Amount vs Device Trust Score

---

## Dashboard 3 — Customer & Merchant Analysis

### KPIs
- Average Cardholder Age
- Highest Fraud Merchant Category

### Charts
- Fraud by Age Group
- Fraud Amount by Merchant Category
- Merchant Category Distribution
- Merchant Fraud Share

---

## Dashboard 4 — Fraud Investigation

### KPIs
- Highest Fraud Amount
- Average Fraud Amount
- Average Fraud Velocity
- Average Device Trust Score

### Charts
- Fraud Amount by Merchant Category
- Fraud by Transaction Hour
- Risk Scatter Analysis
- Transaction Velocity Analysis

### Investigation Table
- Transaction ID
- Merchant Category
- Amount
- Transaction Hour
- Device Trust Score
- Velocity
- Foreign Transaction
- Location Mismatch
- Fraud Status

---

# 📈 DAX Measures

- Total Transactions
- Fraud Transactions
- Fraud Rate %
- Fraud Amount
- Average Transaction Amount
- Highest Fraud Amount
- Average Fraud Amount
- Average Fraud Velocity
- Average Device Trust Score

---

# 🔍 Key Insights

- Fraud is concentrated within specific merchant categories.
- Foreign transactions show a higher fraud frequency.
- Lower device trust scores are associated with higher fraud risk.
- High transaction velocity increases the likelihood of fraudulent activity.
- Certain transaction hours experience noticeably higher fraud volumes.

---

# 🎨 Dashboard Features

- Interactive slicers
- KPI Cards
- Drill-down capability
- Conditional formatting
- Cross-filtering visuals
- Clean and responsive layout

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Modeling
- DAX Calculations
- KPI Design
- Interactive Dashboard Development
- Business Intelligence
- Fraud Analytics
- Data Visualization

---

## 📷 Dashboard Preview

> Add screenshots of all four dashboard pages here.

```
Dashboard 1 Screenshot

Dashboard 2 Screenshot

Dashboard 3 Screenshot

Dashboard 4 Screenshot
```

---

## 🚀 Future Improvements

- Add real-time transaction monitoring.
- Integrate fraud detection using machine learning.
- Include branch, city, and customer information for deeper analysis.
- Implement fraud alert thresholds.
- Publish the dashboard to the Power BI Service

Power BI | SQL | Excel | Data Analytics

---

## ⭐ If you found this project useful, consider giving the repository a star.
