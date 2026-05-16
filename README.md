# 🏠 Household Financial Analysis

> Analyzing 10,000 households to uncover the financial patterns behind income, debt, education, and regional inequality.

---

## 📌 Project Overview

This end-to-end data analysis project explores household financial data using **Python**, **SQL (SQLite)**, and **Power BI**. The goal was to identify key financial drivers — from education and employment to regional wealth gaps and spending behavior.

**Dataset:** 10,000 household records → cleaned to **9,651 rows**  
**Tools:** Python · pandas · SQLite · Matplotlib · Seaborn · Power BI

---

## 📊 Dashboard Preview

![Household Financial Analysis Dashboard](dashboard_screenshot.png)

> Built in Power BI — dark theme with KPI cards, spending breakdown, income by education, debt by employment, and regional wealth comparisons.

---

## 🗂️ Project Structure

```
household-financial-analysis/
│
├── README.md
├── dashboard_screenshot.png
│
├── data/
│   └── data.csv                          # Raw dataset
│
├── notebook/
│   └── household_financial_analysis.ipynb  # Full analysis (SQL + Python + Viz)
│
└── powerbi/
    └── household_data.pbix               # Power BI dashboard file
```

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
| Negative income/earnings | Kept — represent valid debt/loss cases |
| Duplicates | Checked — none found |
| Final row count | 10,000 → **9,651 clean rows** |

---

## 🔍 SQL Analysis — 7 Key Questions

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

## 📈 Visualizations (Phase 4)

| Visual | Chart Type | Insight |
|---|---|---|
| V1 | Line Chart | Income trend by education years |
| V2 | Bar Chart | Regional wealth gap |
| V3 | Pie Chart | Spending category distribution |
| V4 | Bar Chart | Debt by employment status |
| V5 | Heatmap | Income by region × employment |

---

## 💡 Top 5 Business Insights

### 1️⃣ Education Drives Wealth
Higher education years directly correlate with higher income, wealth, and savings. Education investment is the most powerful lever for poverty reduction.

### 2️⃣ Regional Inequality Is Real
Top regions show significantly higher average wealth than bottom regions. An urban-rural divide is clearly visible across income and savings data.

### 3️⃣ Unemployment = Debt Trap
Unemployed households carry the highest average debt and lowest savings — leaving them with no buffer against financial shocks.

### 4️⃣ Microcredit Matters
Households with microcredit access show different spending patterns. High debt + no microcredit = most financially vulnerable group.

### 5️⃣ Food Dominates Spending
Food is the largest expense category (~34%), limiting available budget for education and health investment.

---

## 🚀 Policy Recommendations

- 📚 Expand quality education access in low-income regions
- 💼 Create employment programs targeting high-debt unemployed households
- 💳 Scale microcredit access to underserved rural regions
- 🛒 Implement food subsidy schemes for below-average income households

---

## 🤝 Connect

**LinkedIn:** [https://www.linkedin.com/in/jiveshh/]  


---

*Made with Python, SQL & Power BI*
