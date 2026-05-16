# 🏠 Household Financial Analysis

> Analyzing 10,000 households to uncover the financial patterns behind income, debt, education, and regional inequality.

---

## 📌 Project Overview

This end-to-end data analysis project explores household financial data using **Python**, **SQL (SQLite)**, and **Power BI**. The goal was to identify key financial drivers - from education and employment to regional wealth gaps and spending behavior.

**Dataset:** 10,000 household records → cleaned to **9,651 rows**
**Tools:** Python · pandas · SQLite · Matplotlib · Seaborn · Power BI

---

## 🔧 Tools & Technologies

| Tool | Purpose |
|---|---|
| Python + pandas | Data loading, cleaning, EDA |
| SQLite + SQL | Structured querying & aggregation |
| Matplotlib + Seaborn | Data visualizations |
| Power BI | Interactive dashboard |
| Jupyter Notebook | End-to-end analysis workflow |

---

## 🧹 Data Cleaning

| Step | Action |
|---|---|
| Null values | Dropped rows with missing `savings` & `expenditure_health` |
| Negative income/earnings | Kept - represent valid debt/loss cases |
| Duplicates | Checked - none found |
| Final row count | 10,000 → **9,651 clean rows** |

---

## 🔍 SQL Analysis - 7 Key Questions

| # | Question | SQL Concepts |
|---|---|---|
| Q1 | Average income by education level | AVG, GROUP BY, ORDER BY |
| Q2 | Region with highest average wealth | AVG, GROUP BY, ORDER BY |
| Q3 | Employment status vs average debt | AVG, GROUP BY |
| Q4 | Gender-wise income comparison | AVG, GROUP BY |
| Q5 | Region with highest microcredit access | AVG, GROUP BY |
| Q6 | Average spending breakdown by category | AVG, SELECT |
| Q7 | Income of households with vs without subsidy | AVG, GROUP BY |

---

## 💡 Top 5 Business Insights

**1️⃣ Education Drives Wealth** - Higher education years directly correlate with higher income, wealth, and savings.

**2️⃣ Regional Inequality Is Real** - Top regions show significantly higher average wealth. Urban-rural divide is clearly visible.

**3️⃣ Unemployment = Debt Trap** - Unemployed households carry highest average debt with lowest savings.

**4️⃣ Microcredit Matters** - High debt + no microcredit = most financially vulnerable group.

**5️⃣ Food Dominates Spending** - Food is the largest expense (~34%), limiting budget for education and health.

---

## 🚀 Policy Recommendations

- 📚 Expand quality education access in low-income regions
- 💼 Employment programs targeting high-debt unemployed households
- 💳 Scale microcredit access to underserved rural regions
- 🛒 Food subsidies for below-average income households

---

## 🤝 Connect

**LinkedIn:** [https://www.linkedin.com/in/jiveshh/]

---

*Made with Python, SQL & Power BI*
