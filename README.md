# 🏦 Bank Loan Analysis

This project presents an end-to-end analysis of a bank’s loan portfolio using **MS SQL Server for data exploration**, **Excel for KPI dashboards**, and a detailed **PDF report** to communicate insights. It covers key performance metrics, identifies good vs. bad loans, and visualizes trends to support data-driven decision-making.

---

## 📊 Project Overview

The objective of this project is to evaluate and monitor the performance of bank lending activities by:
- Identifying key KPIs (e.g., funded amount, interest rate, DTI)
- Segmenting loans by status: *Good* (Fully Paid, Current) vs *Bad* (Charged Off)
- Visualizing trends across states, loan purposes, and borrower characteristics

This project helps business stakeholders understand loan health, repayment trends, and risk exposure.

---

## 🛠️ Tools Used

- **MS SQL Server** – for data exploration & analysis
- **Microsoft Excel** – for building dashboards
- **Word/PDF** – for documentation and reporting

---

## 📈 Key Dashboards

### 🔹 Summary Dashboard
- Total Loan Applications (Overall, MTD, MoM)
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average DTI

### 🔹 Good vs Bad Loans
- Application Count & %
- Funded & Received Amount by Loan Status

### 🔹 Overview Dashboard
- Monthly Trends (Line Chart)
- State-wise Lending (Map)
- Loan Term (Donut Chart)
- Employment Length & Loan Purpose (Bar Charts)
- Home Ownership (Tree Map)

---

## 🧠 Key Insights

- Majority of loans are 36-month terms with high funding in CA, NY, and TX
- Average interest rate trends remain consistent month-over-month
- Higher DTI ratios observed in Charged Off loans
- Fully Paid and Current loans account for over 70% of the portfolio

---

## 🔍 Getting Started

1. Clone the repo
2. Explore the dataset (`financial_loan.csv`)
3. Run SQL scripts `EDA_Queries1.sql` and `EDA_Queries2.sql`
4. Open Excel dashboards to view metrics and trends
5. Read the final report in `Bank Loan Analysis Report`

---
