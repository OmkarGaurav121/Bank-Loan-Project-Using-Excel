# 📊 Bank Loan Analysis Using Excel

A complete Excel-based analytical and dashboard project to explore and derive insights from a bank’s financial loan data. This project demonstrates how Excel can be used for data cleaning, transformation, visualization, and business reporting.

---

## 📌 Table of Contents

- [Problem Statement](#-problem-statement)
- [Objectives](#-objectives)
- [Tools Used](#-tools-used)
- [Dataset Overview](#-dataset-overview)
- [Data Cleaning](#-data-cleaning)
- [Dashboard Screenshots](#-dashboard-screenshots)
  - [Overview Dashboard](#overview-dashboard)
  - [Summary Dashboard](#summary-dashboard)
- [Insights & Explanations](#-insights--explanations)
- [Challenges Faced](#-challenges-faced)
- [Conclusion](#-conclusion)
- [How to Use](#-how-to-use)
- [Author](#-author)
- [License](#-license)

---

## 🔍 Problem Statement

Financial institutions need robust loan approval strategies. This project analyzes historical loan data to uncover approval trends, assess risk profiles, and optimize decisions using Excel dashboards.

---

## 🎯 Objectives

- Clean, transform, and structure loan data for analysis.
- Build interactive dashboards for monitoring KPIs.
- Identify behavioral and financial patterns in loan applicants.
- Present findings visually to aid business decisions.

---

## 🧰 Tools Used

- **Microsoft Excel**
  - Power Query for data cleaning
  - Pivot Tables & Pivot Charts
  - Slicers and Timelines
  - Conditional Formatting
- **Visualization Style**: Dark Theme Dashboard
- **Data Format**: CSV → Excel Workbook

---

## 🧾 Dataset Overview

The dataset contains ~38,600 loan applications with fields such as:

| Column | Description |
|--------|-------------|
| `Loan_ID` | Unique loan identifier |
| `Gender`, `Married`, `Dependents` | Applicant demographics |
| `Education`, `Self_Employed` | Employment/qualification status |
| `ApplicantIncome`, `LoanAmount` | Financial details |
| `Loan_Status` | Loan approved (Y/N) |
| `Credit_History`, `Property_Area` | Risk metrics |

---

## 🧹 Data Cleaning

Performed in **Excel Power Query**:
- Removed null values and inconsistencies.
- Replaced “3+” dependents with numeric `3`.
- Filled missing credit histories and loan amounts.
- Derived fields:
  - `TotalIncome = Applicant + Coapplicant`
  - `DTI = Debt-to-Income ratio`

---

## 🖼 Dashboard Screenshots

### 🟦 Overview Dashboard

![Overview Dashboard](Overview%20Dashboard.png)

This dashboard offers a **high-level summary of all loan applications**, KPIs, and trends:

#### Components:
- 📌 **Top KPIs**: Total Applications, Funded Amount, Interest Rate, DTI.
- 📈 **Line Chart**: Monthly application trends.
- 🗺 **Choropleth Map**: Applications by US State.
- 🥧 **Pie Chart**: Term-wise distribution (36 vs 60 months).
- 📊 **Bars**:
  - Applications by Employment Length
  - Applications by Purpose (e.g., Credit Card, Education)
  - Ownership Type: Mortgage, Rent, Own

---

### 🟨 Summary Dashboard

![Summary Dashboard](Summary%20Dashboard.png)

This page breaks down loans into **Good vs Bad** categories.

#### Components:
- ✅ **Good Loans**:
  - % Share, Applications, Amount Funded, Amount Received
- ❌ **Bad Loans**:
  - % Share, Applications, Amount Funded, Received
- 📊 **Loan Status**: Fully Paid, Current, Charged Off
- 💰 **Metric Charts**: Funded Amount, Interest Rate, DTI – grouped by status

---

## 🔎 Insights & Explanations

| Insight | Explanation |
|--------|-------------|
| **86.18% of loans are classified as Good** | Indicates strong credit-based filtering. |
| **Credit card loans dominate applications** | Over 18K loans for credit card purposes—high demand. |
| **Applicants with 10+ years experience are more likely approved** | Reflects trust in experienced applicants. |
| **Most loans are 36-month terms** | Suggests shorter-term loans are favored for faster returns. |
| **States like California and Texas lead in loan applications** | High population and credit penetration. |
| **Interest rates vary significantly by loan status** | Bad loans show higher average rates (15%+). |

---

## ❗ Challenges Faced

- Missing values in critical fields like `Credit_History` and `LoanAmount`.
- Ambiguities in employment lengths and dependents.
- Balancing visual simplicity with analytical depth in dashboards.

---

## ✅ Conclusion

Excel is a powerful tool for financial analysis and dashboarding. This project showcases its strength in transforming raw data into meaningful business visuals and insights—without needing any code.

---

## 💻 How to Use

1. Download or clone the repository.
2. Open `Bank Loan Excel Project.xlsx`.
3. Navigate to the `Overview` and `Summary` dashboard sheets.
4. Use slicers (Grade, Purpose) to interactively filter data.

---

## 👤 Author

**Omkar Gaurav**  
📎 GitHub: [OmkarGaurav121](https://github.com/OmkarGaurav121)

---

## 📃 License

This project is licensed under the MIT License.
