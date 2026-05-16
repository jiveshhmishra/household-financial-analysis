🏠 Household Financial Analysis

Analyzing 10,000 households to uncover the financial patterns behind income, debt, education, and regional inequality.


📌 Project Overview
This end-to-end data analysis project explores household financial data using Python, SQL (SQLite), and Power BI. The goal was to identify key financial drivers — from education and employment to regional wealth gaps and spending behavior.
Dataset: 10,000 household records → cleaned to 9,651 rows
Tools: Python · pandas · SQLite · Matplotlib · Seaborn · Power BI

🔧 Tools & Technologies
ToolPurposePython + pandasData loading, cleaning, EDASQLite + SQLStructured querying & aggregationMatplotlib + SeabornData visualizationsPower BIInteractive dashboardJupyter NotebookEnd-to-end analysis workflow

🧹 Data Cleaning
StepActionNull valuesDropped rows with missing savings & expenditure_healthNegative income/earningsKept — represent valid debt/loss casesDuplicatesChecked — none foundFinal row count10,000 → 9,651 clean rows

🔍 SQL Analysis — 7 Key Questions
#QuestionSQL ConceptsQ1Average income by education levelAVG, GROUP BY, ORDER BYQ2Region with highest average wealthAVG, GROUP BY, ORDER BYQ3Employment status vs average debtAVG, GROUP BYQ4Gender-wise income comparisonAVG, GROUP BYQ5Region with highest microcredit accessAVG, GROUP BYQ6Average spending breakdown by categoryAVG, SELECTQ7Income of households with vs without subsidyAVG, GROUP BY

💡 Top 5 Business Insights
1️⃣ Education Drives Wealth — Higher education years directly correlate with higher income, wealth, and savings.
2️⃣ Regional Inequality Is Real — Top regions show significantly higher average wealth. Urban-rural divide is clearly visible.
3️⃣ Unemployment = Debt Trap — Unemployed households carry highest average debt with lowest savings.
4️⃣ Microcredit Matters — High debt + no microcredit = most financially vulnerable group.
5️⃣ Food Dominates Spending — Food is the largest expense (~34%), limiting budget for education and health.

🚀 Policy Recommendations

📚 Expand quality education access in low-income regions
💼 Employment programs targeting high-debt unemployed households
💳 Scale microcredit access to underserved rural regions
🛒 Food subsidies for below-average income households


🤝 Connect
LinkedIn: [your-linkedin-url]
GitHub: [your-github-url]

Made with Python, SQL & Power BI
