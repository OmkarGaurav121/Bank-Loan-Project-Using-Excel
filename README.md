# 🏦 Excel Bank Loan Analysis Dashboard

![Excel Project](https://img.shields.io/badge/Excel-Loan%20Analysis-green)
![Status](https://img.shields.io/badge/Status-Completed-blue)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A comprehensive Excel-based loan performance analysis project that uses dashboards and KPIs to evaluate and visualize key financial metrics in the banking sector.

---

## 📋 Table of Contents
- [📌 Problem Statement](#-problem-statement)
- [🎯 Objectives](#-objectives)
- [🧰 Tools Used](#-tools-used)
- [📊 Dataset Info](#-dataset-info)
- [🧹 Data Cleaning & Processing](#-data-cleaning--processing)
- [📈 Dashboards](#-dashboards)
- [🔍 Key Insights](#-key-insights)
- [⚙️ Challenges Faced](#️-challenges-faced)
- [✅ Conclusion](#-conclusion)
- [📎 How to Use](#-how-to-use)
- [🙋‍♂️ About Me](#-about-me)
- [📝 License](#-license)

---

## 📌 Problem Statement

Banks handle thousands of loan applications daily. This project aims to analyze and visualize loan performance data to assist banks in:
- Monitoring active, paid, and defaulted loans
- Improving decision-making processes
- Enhancing customer targeting strategies

---

## 🎯 Objectives

- Clean and structure financial loan data
- Create visually informative dashboards in Excel
- Highlight key metrics (loan status, term, purpose, etc.)
- Extract business-level insights from the visual data

---

## 🧰 Tools Used

- **Microsoft Excel**
  - Power Query for data cleaning
  - Pivot Tables & Charts
  - Slicers & Timelines
  - Dashboard Design & Formatting
- Optional (for source tracking): GitHub

---

## 📊 Dataset Info

- **Source**: Provided `financial_loan.csv`
- **Size**: ~10,000+ records
- **Fields**: Loan Status, Interest Rate, Loan Amount, Purpose, Term, Grade, etc.

🔗 [Download Sample Dataset](./financial_loan.csv)

---

## 🧹 Data Cleaning & Processing

Performed in **Excel Power Query Editor**:
- Removed blank/null rows and columns
- Converted text fields to lowercase
- Removed duplicates
- Standardized column names
- Corrected inconsistent date formats
- Transformed interest rate to numeric

---

## 📈 Dashboards

### 🟢 Overview Dashboard

![Overview Dashboard](Images/Overview%20Dashboard.png)

- Overall loan health distribution
- Interest rates by term and grade
- Filters by loan status, purpose, and year

---

### 🔵 Summary Dashboard

![Summary Dashboard](Images/Summary%20Dashboard.png)

- Key KPIs: Total Funded Amount, Outstanding Principal, Interest Received
- Visual breakdowns by Loan Status and Purpose
- Year-on-year loan issuance trends

---

## 🔍 Key Insights

| Insight No. | Description |
|-------------|-------------|
| 1️⃣ | Over 60% of the loans are Fully Paid; 10% Charged Off |
| 2️⃣ | Most loans fall under the category of **Personal** or **Debt Consolidation** |
| 3️⃣ | Grade B and C dominate loan approvals |
| 4️⃣ | Default rates are highest in **Small Business** category |
| 5️⃣ | Longer-term loans have higher interest rates |
| 6️⃣ | Q4 shows highest loan disbursements year-on-year |

---

## ⚙️ Challenges Faced

- Converting mixed-type columns (e.g., % Interest)
- Cleaning inconsistent "Loan Status" values
- Designing interactive dashboards without VBA
- Ensuring performance with large datasets

---

## ✅ Conclusion

This Excel Dashboard provides a complete 360° view of loan performance, allowing financial institutions to:
- Understand customer behavior
- Detect risk patterns
- Plan better loan strategies

It's a great example of how Excel can be used not just for calculation, but for **decision intelligence**.

---

## 📎 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Excel-Bank-Loan-Project.git
