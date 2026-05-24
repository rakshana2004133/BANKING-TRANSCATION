# 🏦 Banking Transaction Dashboard – Power BI Project

## 📌 Project Overview
The Banking Transaction Dashboard is a Power BI project developed to analyze banking transactions, customer loan activities, KYC verification status, merchant categories, and transaction channels.  

This dashboard transforms raw banking transaction data into meaningful business insights using interactive visualizations and KPI cards.

---

# 🎯 Objectives
- Analyze banking transaction data effectively
- Monitor customer loan activities
- Track customer KYC verification status
- Identify transaction trends across states
- Analyze transaction channels and merchant categories
- Provide interactive business insights using Power BI

---

# 📂 Dataset Description
The dataset contains banking transaction details such as:

- Transaction Amount
- Account Balance
- EMI Amount
- Loan Type
- Merchant Category
- Transaction Channel
- KYC Status
- State Information

---

# 🛠️ Tools & Technologies Used
- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Excel / CSV
- Python & Pandas

---

# 📊 Dashboard Features

## ✅ KPI Cards
Displays:
- Total Transaction Amount
- Account Balance
- EMI Amount

## ✅ State-wise Transaction Analysis
Shows transaction performance across different states.

## ✅ Loan Type Distribution
Analyzes customer loan categories such as:
- Personal Loan
- Home Loan
- Auto Loan
- Business Loan

## ✅ KYC Status Analysis
Tracks customer verification status:
- Verified
- Pending
- Expired

## ✅ Merchant Category Analysis
Analyzes transaction activities across different business sectors.

## ✅ Transaction Channel Analysis
Displays transactions performed through:
- Mobile App
- ATM
- Web
- Branch
- POS Terminal

---

# 🧹 Data Cleaning & Transformation
The dataset was cleaned using:
- Power Query
- Python Pandas

### Steps Performed:
- Removed duplicate records
- Handled missing values
- Corrected data types
- Created calculated fields

---

# 📈 DAX Measures Used

```DAX
Total Transaction = SUM(transaction_amount)

Average EMI = AVERAGE(emi_amount)

Loan Count = COUNT(has_loan)

MTD = TOTALMTD([Transaction Amount], Date)
# BANKING-TRANSCATION
