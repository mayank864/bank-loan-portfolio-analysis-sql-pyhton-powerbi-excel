# bank-loan-portfolio-analysis-sql-pyhton-powerbi-excel
# 🏦 Bank Loan Portfolio Analysis & Performance Dashboard

**Author:** [Mayank Raj](https://www.linkedin.com/in/mayank-raj-12aa36368/)  
**Dataset:** [Financial Loan Dataset (Kaggle)](https://www.kaggle.com/datasets/datawitharyan/financial-loan-dataset)

---

## 📋 Project Overview
In the highly competitive banking sector, monitoring the health of a loan portfolio is critical for mitigating financial risk and optimizing lending strategies. This project delivers a comprehensive, end-to-end data solution designed to monitor key lending KPIs, observe monthly trends, track asset quality, and break down borrower profiles.

By distinguishing between "Good Loans" and "Bad Loans," this analysis helps stakeholders understand the bank's operational health, repayment efficiencies, and potential default vulnerabilities.

---

## 🛠️ Tech Stack & Methodology
This project demonstrates a full-stack data analysis workflow, utilizing multiple tools for different stages of the data pipeline:

* **SQL (`Bank_Loan_Report_SQL.docx`):** Used to write optimized queries to aggregate millions of data points, calculate Month-over-Month (MoM) metrics, and establish a single source of truth for the KPIs.
* **Python (`Bank Loan Analysis.ipynb`):** Utilized for Exploratory Data Analysis (EDA), automated data cleaning, and programmatic visualizations using Pandas, Matplotlib, and Seaborn.
* **Excel (`bank-loan-analysis-excel.xlsx`):** Employed for initial data exploration, quick validation checks, data profiling, and Pivot Table summarizations.
* **Power BI (`bank report.pbix`):** Built the final interactive, high-performance semantic model and designed the multi-view reporting dashboards.

---

## 🎯 Key Performance Indicators (KPIs)
The project tracks several high-level financial metrics, calculating Month-to-Date (MTD) performance and Month-over-Month (MoM) growth:
* **Total Loan Applications:** Tracking the velocity of loan requests.
* **Total Funded Amount:** The total capital disbursed by the bank to borrowers.
* **Total Amount Received:** Total cash recovered (principal + interest) to evaluate immediate cash flows.
* **Average Interest Rate:** Monitoring the portfolio's yield across different asset classes.
* **Average Debt-to-Income (DTI) Ratio:** Assessing borrower financial stress levels and risk exposure.

---

## ⚖️ Business Logic: Good vs. Bad Loans
To evaluate portfolio quality cleanly, loans are classified into two distinct buckets based on their operational status:

### 🟢 Good Loans
* **Criteria:** Loan status is either *'Fully Paid'* or *'Current'*.
* **Metrics Tracked:** Total Good Loan applications, percentage of the total portfolio, and total funded vs. total received amount.

### 🔴 Bad Loans
* **Criteria:** Loan status is *'Charged Off'* (Defaulted).
* **Metrics Tracked:** Total Bad Loan applications, percentage of the total portfolio, and total funded amount vs. total lost/unrecovered capital.

---

## 📊 Dashboard Architecture & Visuals

### 1️⃣ Dashboard 1: Summary View
Designed for C-suite executives to monitor high-level portfolio health instantly. It features dynamic KPI cards displaying total metrics with MoM growth percentages, and a clear Good vs. Bad Loan grid split comparing volume, funding, and recovery rates.

![Summary Dashboard]([Dashboard_1.jpg](https://github.com/mayank864/bank-loan-portfolio-analysis-sql-pyhton-powerbi-excel/blob/main/Dashboard_1.png))

### 2️⃣ Dashboard 2: Overview (Trends & Breakdown)
Designed for risk analysts to identify underlying seasonal patterns and demographic shifts through various visualizations:
* **Monthly Trends (Line Chart):** Observes seasonality variations in funding and applications.
* **Regional Analysis (Filled Map):** Explores lending distribution across states.
* **Loan Term (Donut Chart):** Breaks down short-term (36 months) vs. long-term (60 months) volume.
* **Employee Length & Purpose (Bar Charts):** Analyzes borrower stability profiles and the intent behind loans.

![Overview Dashboard](Dashboard_2.jpg)

### 3️⃣ Dashboard 3: Details View
A deep-dive data grid designed for operational teams who need granular access to individual records. It provides a comprehensive, searchable tabular view of all vital borrower fields with advanced cross-filtering capabilities.

![Details Dashboard](Dashboard_3.jpg)

---

## 🚀 How to Use This Repository
1. **Dataset:** Download the raw data from the [Kaggle link](https://www.kaggle.com/datasets/datawitharyan/financial-loan-dataset) or use the provided CSV/Excel files.
2. **Python Analysis:** Open `Bank Loan Analysis.ipynb` in Jupyter Notebook or VS Code to review the EDA and data cleaning steps.
3. **SQL Queries:** Review `Bank_Loan_Report_SQL.docx` for the exact queries used to validate the dashboard KPIs.
4. **Power BI Dashboard:** Download `bank report.pbix` and open it in Power BI Desktop to interact with the dashboards. 

---

## 📬 Contact
* **LinkedIn:** [Mayank Raj](https://www.linkedin.com/in/mayank-raj-12aa36368/)
* **Email:** [rajmayank362@gmail.com](mailto:rajmayank362@gmail.com)
