**📊 FP&A Financial Performance Dashboard — Power BI**

A compact, high-impact financial analytics project using hybrid data.

**🧾 Overview**

This project showcases a modern FP&A dashboard built in Power BI, combining:

Real UK financial benchmarks (Companies House)

A structured synthetic dataset simulating 36 months of revenue, expenses, cashflow, and customer activity

The goal is to demonstrate core FP&A, BI, and data modelling skills used in real business environments.

**📂 Dataset Summary**
Hybrid Data

Real Data (Benchmarking Only):
UK Companies House Financial Accounts
🔗 https://download.companieshouse.gov.uk/en_accountsdata.html

Synthetic Operational Data (Used in Model):

FactRevenue — revenue by customer × product

FactExpenses — department & category-level expenses

FactCashflow — operating, investing, financing flows

FactBudget — budgeted revenue, COGS, OPEX

CustomerFirstPurchase — customer cohort mapping

CustomerMonthlyActivity — retention activity

DimDate, DimCustomer, DimProduct, DimDepartment

Structured in a star schema and optimized for DAX time intelligence.

**📈 Dashboard Sections**
**1️⃣ Executive Summary
**
Revenue, Gross Profit, Operating Profit, Net Profit

Cash Balance

YoY / MoM growth

Revenue vs Expense trends

**2️⃣ Profit & Loss Deep Dive**

Revenue breakdown (Product / Region / Segment)

COGS & Operating Expense analysis

Gross Margin by product/segment

Budget vs Actuals (waterfall variance)

**3️⃣ Cashflow & Liquidity
**
Operating / Investing / Financing cashflow

Free Cash Flow

Burn Rate analysis

Cash Runway (with What-If parameter)

Working capital indicators (AR/AP/DSO/DPO)

**4️⃣ Customer & Segment Insights**

Profitability heatmap (Segment × Region)

Cohort retention matrix

LTV (Lifetime Value) modelling

Top customers (Pareto 80/20)

Segment contribution analysis

**🛠️ Skills Demonstrated**

Power BI (data modelling, DAX, parameters, time intelligence)

Financial analysis (P&L, cashflow, budget variance, margins)

Cohort & retention modelling

Liquidity runway + burn analysis

Customer lifetime value (LTV)

Dashboard storytelling & visual design

**📁 Repository Structure**
data/        → CSV files (facts + dimensions)
pbix/        → FP&A Dashboard Power BI file
README.md    → Project documentation
images/      → Screenshots (optional)

**👩‍💻 Author
**
Yashvi Pandya
Data Analyst | FP&A | Power BI
London, UK

Forecast intervals
