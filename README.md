**Bank Loan Analysis Project**
**Overview**
This data analysis project examines bank loan data to uncover insights on lending operations, loan performance, and borrower trends. Inspired by a YouTube tutorial, it showcases skills in SQL querying, data processing, and Power BI visualization. Key metrics include loan applications, funded amounts, repayments, interest rates, DTI ratios, and good vs. bad loan distinctions.

**Technologies Used**
**Database:** MS SQL Server (adaptable to MySQL)
**Querying:** SQL (aggregations, filters, groupings)
**Visualization:** Power BI (DAX, charts, dashboards)
**Other:** Power Query for data cleaning

**Key Features**
KPIs and Metrics
**Total Applications:** 38.6K; Funded: $435.8M; Received: $473.1M; Avg Interest: 12.0%; Avg DTI: 13.3%.
**Good Loans: **86.2% ($370.2M funded, $435.8M received).
**Bad Loans:** 13.8% ($65.5M funded, $37.3M received).
MTD/MoM comparisons via SQL queries.

**Dashboards**
**Summary: **KPIs, good/bad pie charts, loan status grid.
**Overview:** Monthly trends (line), regional map, term donut, employee bar, purpose bar, ownership tree map.
**Details:** Tabular loan records with filters.

**Data Validation**
SQL queries (from attached PDF) cross-verified Power BI results, e.g., total funded: SELECT SUM(loan_amount) FROM financial_loan;.
Insights
Rising monthly funds; high activity in CA/TX; common purposes: credit card, weddings.

**How to Run**
Set up database with financial_loan table.
Run SQL queries for data extraction.
Connect Power BI to database; build dashboards.
Clone repo: https://github.com/Krishagrawal-046/-Bank-Loan-Analysis-Dashboard-.git
Open .pbix file in Power BI.
