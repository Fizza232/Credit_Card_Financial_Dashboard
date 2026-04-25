# Credit Card Financial Dashboard

**Type:** Data Analytics Project | **Tool:** Power BI + SQL

An interactive Power BI dashboard built using transaction and customer data from a SQL database to analyze credit card business performance, customer demographics, and spending patterns.

Designed as a portfolio project to demonstrate data analysis, SQL-based data extraction, and business insight generation skills.

## Objective

To analyze and monitor credit card business performance by evaluating revenue, interest earned, and transaction patterns across customer segments and spending categories.

## Dashboard Preview

**Transaction Report**

![Credit Card Transaction Dashboard](https://github.com/user-attachments/assets/f95b9b98-cf02-4925-9601-f3c1797376cf)

**Customer Report**

![Credit Card Customer Dashboard](https://github.com/user-attachments/assets/66571062-6b8b-4215-9491-512fd20a4018)

---

## Dataset

* `credit_card.csv` — Transaction-level credit card data containing:

  * Card category, transaction amount, interest earned
  * Payment mode (Swipe, Chip, Online)
  * Expenditure type, week number, quarterly data
* `customer.csv` — Customer demographic details containing:

  * Age group, income level, education, job type
  * State, dependent count, satisfaction score
* `SQL database` — Data extraction and transformation layer

---

## Tools & Technologies

* **Power BI** — Dashboard design, data modeling, and visualizations
* **Power Query** — Data cleaning & transformation
* **DAX** — KPI calculations (Revenue, Interest Earned, WoW variance, Activation Rate)
* **SQL** — Data extraction & transformation from relational database
* **CSV** — Raw data source

---

## Key Features

**Transaction Report**

* Total Revenue (57M), Transaction Amount (45.5M), Interest Earned (8M), Transaction Count (667.2K)
* Revenue breakdown by card category, expenditure type, and payment mode
* Week-over-week (WoW) revenue variance tracking
* Quarterly revenue and transaction count comparison (Q1–Q4)

**Customer Report**

* Revenue segmented by age group, income level, education, and job type
* State-wise and dependent-count revenue distribution
* Customer Satisfaction Score (CSS): 3.19
* 30-day activation rate: 57.46%
* Delinquency rate analysis by customer job segment

---

## Key Insights

* Total revenue stands at **$57M** with **$8M** in interest earned across 667K+ transactions
* **Blue card holders** generate the highest revenue at **$47M** out of total $57M
* **Swipe transactions** dominate at **$36M**, compared to Chip ($17M) and Online ($4M)
* **Graduate customers** contribute the highest revenue at **$23M** by education type
* **Businessmen** lead revenue by job category at **$18M**
* **Q4** recorded the highest transaction count at **173.2K**
* **57.46%** of customers activated their card within 30 days

---

## Business Impact

This dashboard enables financial teams to:

* Monitor real-time credit card revenue and transaction performance
* Identify high-value customer segments for targeted marketing
* Track delinquency risk and activation rates for operational decisions
* Analyze spending behavior across categories to optimize card offerings

---

## How to Use

1. Download the `.pbix` file from this repository
2. Open in **Power BI Desktop** (free download at [powerbi.microsoft.com](https://powerbi.microsoft.com))
3. The dashboard loads with all data pre-connected — no additional setup required
4. Use quarter filters (Q1–Q4) and gender/card-type slicers to explore the data
5. Hover over any chart for detailed tooltips
6. To connect your own SQL database, go to **Home → Transform Data** and update the data source connection

---

## Project Structure

```
Credit_Card_Financial_Dashboard/
├── Credit_Card_Financial_Dashboard.pbix    # Power BI dashboard file
├── Credit_Card_Transaction_Dashboard.sql   # SQL queries for data extraction
├── credit_card.csv                         # Transaction dataset
├── customer.csv                            # Customer dataset
├── Credit_Card_Report_transaction.pdf      # Transaction report (static export)
└── Credit_Card_Report_customer.pdf         # Customer report (static export)
```

---

## Author

**Fizza Shabbir** — [LinkedIn](https://linkedin.com/in/fizzashabbir) | [GitHub](https://github.com/Fizza232)
