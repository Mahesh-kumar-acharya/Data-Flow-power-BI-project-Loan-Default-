# Data-Flow-power-BI-project-Loan-Default-
Power BI dashboard analyzing 255K+ loan records to uncover default patterns by age, credit score, employment &amp; more. Built with SQL Server, Power Query &amp; DAX.

# Loan Default Analytics Dashboard (Power BI)

An end-to-end loan analytics dashboard built on **255,347 loan records (2013–2018)** to understand who defaults and why.

## Tech Stack
SQL Server · Power BI Dataflows · Power Query · DAX · Power BI Service

## Dataset
- 255,347 rows, 19 columns, no missing values or duplicate loan IDs
- Fields: age, income, loan amount, credit score, employment type, education, marital status, mortgage, dependents, loan purpose, default flag, loan date

## Dashboard Pages
1. **Loan Default & Overview**: default rate by year, employment type, age group, loan purpose
2. **Financial Risk Metrics**: YoY loan and default change, YTD loan amount, decomposition tree
3. **Applicant Demographics & Financial Profile**: credit score bins, age/marital status, education, mortgage and dependents

## Key DAX Measures
- Default Rate
- Average / Median Loan Amount
- YoY Change
- YTD Loan Amount

## Key Insights
- Overall default rate is **11.6%**
- Borrowers aged **18–29 default at ~19.7%** vs ~5.1% for ages 60+
- **Unemployed** borrowers default at 13.6% vs 9.5% for full-time
- Credit score has only a weak effect (12.5% for <580 vs 9.8% for 800+)

## Features
- Data validation in Power Query
- Scheduled and incremental refresh
- Published and shared via Power BI Service


## How to Open
Open `loan_report.pbix` in Power BI Desktop (free). Data source: `data/Loan_default.csv`.
