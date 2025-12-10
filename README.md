**📊 FP&A Financial Performance Dashboard — Power BI**

A compact, high-impact financial analytics project using hybrid data.

**🧾 Overview**

This project showcases a modern FP&A dashboard built in Power BI, combining:

Real UK financial benchmarks (Companies House data)

A structured synthetic dataset simulating 36 months of revenue, expenses, cashflow, and customer activity

The goal is to demonstrate core FP&A, BI, and data modelling skills used in real business environments.

**🖼️ Dashboard Preview**

🔹 ![Executive Dashboard]("pg_1.png")

🔹 ![Profit & Loss Deep Dive]("pg_2.png")

🔹 ![Cashflow & Liquidity Analysis]("pg_3.png")

🔹 ![Customer Insights]("pg_4.png")


**📂 Dataset Summary**

Real Data (Benchmark Only):

UK Companies House Financial Accounts
🔗 https://download.companieshouse.gov.uk/en_accountsdata.html

Synthetic Data (Used in the model):

FactRevenue — revenue by customer × product

FactExpenses — department-level operating & COGS expenses

FactCashflow — operating, investing, financing flows

FactBudget — budgeted revenue, COGS, OPEX

CustomerFirstPurchase — cohort mapping

CustomerMonthlyActivity — monthly retention file

DimDate, DimCustomer, DimProduct, DimDepartment

Structured in a clean star schema and optimised for DAX time intelligence.

**📈 Dashboard Sections**

**1️⃣ Executive Summary**

Revenue, Gross Profit, Operating Profit, Net Profit

YoY & MoM growth

Cash balance

Revenue vs OPEX trend

**2️⃣ Profit & Loss Deep Dive**

Revenue by Product / Region / Segment

COGS & OPEX breakdown

Gross margin analysis

Budget vs Actuals Variance (Waterfall)

**3️⃣ Cashflow & Liquidity**

Operating, Investing, Financing cashflow

Free Cash Flow

Burn Rate

Cash Runway (with What-If scenario)

Working capital metrics (AR/AP/DSO/DPO)

**4️⃣ Customer & Segment Insights**

Profitability heatmap (Segment × Region)

Cohort retention heatmap

Customer LTV

Top customers (Pareto 80/20)

**🛠️ Skills Demonstrated**

Power BI modelling & DAX

Financial analysis (P&L, cashflow, margins, variance)

Time intelligence (YTD, MoM, YoY)

Cohort modelling & retention analysis

Liquidity runway & burn modelling

LTV calculation

Data storytelling & dashboard design

**📁 Repository Structure**

data/        → CSV files
images/      → Dashboard screenshots
pbix/        → Power BI file
README.md    → Documentation

**👩‍💻 Author**

Yashvi Pandya
Data Analyst | FP&A | Power BI
London, UK
