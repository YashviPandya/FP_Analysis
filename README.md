📊 FP&A Financial Performance Dashboard — Power BI

A complete end-to-end financial analytics project using a hybrid dataset (real UK benchmarks + synthetic operational data).

📁 Project Overview

This project showcases a full Financial Planning & Analysis (FP&A) dashboard built in Power BI, designed to demonstrate core skills required in finance, analytics, and BI roles.

It uses:

Real UK financial statement data from Companies House (for benchmarking)

A custom-built synthetic operational dataset that simulates revenue, expenses, budgeting, and cashflow across a 36-month period

This dashboard replicates the type of reporting used by FP&A teams in modern UK businesses.

📂 Dataset Description
1. Real Data Source (Benchmarking Only)

UK Companies House — Public Financial Accounts Dataset
🔗 https://download.companieshouse.gov.uk/en_accountsdata.html

(Used only to benchmark realistic finance trends such as revenue growth, expense ratios, and cashflow patterns.)

2. Synthetic Dataset (Created for Analysis)

The synthetic dataset includes complete fact and dimension tables structured in a star schema, ready for BI modelling.

🔹 Fact Tables
File	Description
FactRevenue.csv	Monthly revenue at customer × product level
FactExpenses.csv	Monthly expenses by department and category
FactCashflow.csv	Operating, investing, financing cashflow with ending cash
FactBudget.csv	Monthly budgeted revenue, COGS, and OPEX per product
🔹 Dimension Tables
File	Description
DimDate.csv	Time intelligence table (36 months)
DimCustomer.csv	Customer info with segment & region
DimProduct.csv	Product catalog with pricing & cost
DimDepartment.csv	Department structure for expenses

A data_dictionary.csv is included for reference.

📊 Power BI Dashboard Components
1. Executive KPI Overview

Total Revenue

Gross Profit

Operating Profit

Cash Balance

YoY comparisons

Trending charts

2. Profit & Loss Statement (P&L)

Revenue

COGS

Gross Profit Margin

Operating Expenses

Net Profit Trend

Gross Margin by Product / Customer Segment

3. Budget vs Actuals

Revenue variance

COGS variance

Operating Expense variance

Variance by category

Waterfall chart showing variance drivers

4. Cashflow Analysis

Operating Cashflow

Investing Cashflow

Financing Cashflow

Net Cashflow

Ending Cash runway

Cashflow vs Profit comparison

5. Customer & Product Insights

Revenue by customer segment

Product profitability

Top customers

Region-wise performance

Contribution margin visuals

6. Forecasting (Optional Enhancement)

Using Power BI's built-in forecasting or Python:

3–12 month revenue forecast

Seasonal decomposition

Forecast intervals
