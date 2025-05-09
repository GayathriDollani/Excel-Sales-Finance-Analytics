# Sales and Finance Analytics in Excel

This project uses Excel to develop a comprehensive set of reports aimed at delivering insights into both sales performance and financial health for **Atliq Hardware Technologies**. By harnessing **Power Query, Power Pivot**, and **Data Modeling**, the project provides valuable metrics for decision-making.


## Table of Contents

- [Objective](#objective)
- [Key Features](#key-features)
- [Data and Tools Used](#data-and-tools-used)
- [Purpose of Sales Analytics](#purpose-of-sales-analytics)
- [Purpose of Finance Analytics](#purpose-of-finance-analytics)
- [Workflow Breakdown](#workflow-breakdown)
- [Role of Reports](#role-of-reports)
- [Documentation](#documentation)
- [References](#references)

---

## Objective

The main objective of this project was to create a system of reports that would allow stakeholders at Atliq Hardware Technologies to analyze both sales and financial data at a granular level. This includes tracking market performance, customer behavior, and financial outcomes such as profit and loss, segmented by key dimensions like markets, months, and fiscal years.

---

## Key Features

### Sales Analytics:
- **Market Performance Report**
- **Customer Performance Report**

### Finance Analytics:
- **P&L Statements** by:
  - Market  
  - Month  
  - Fiscal Year

---

## Data and Tools Used

### CSV Files from Atliq Hardware Technologies:
- `dim_customer.csv`: Customer details  
- `dim_product.csv`: Product information  
- `dim_market.csv`: Market segments  
- `fact_sales_monthly.csv`: Monthly sales figures  
- `target.csv`: Market performance targets  

### Excel Features:
- **Power Query** for data cleaning and transformation  
- **Data Model** for relationship building between tables  
- **Power Pivot** for calculated measures  
- **User-friendly** and **visually enhanced reports**

---

## Purpose of Sales Analytics

The Sales Analytics section was designed to offer detailed insights into the performance of markets and customers for Atliq Hardware Technologies, with a focus on:

- Identifying top-performing markets and tracking their sales against targets  
- Understanding customer behavior, including purchasing trends, repeat orders, and overall contribution to sales  

These reports empower the business to optimize its sales strategies by identifying which markets and customers are contributing the most and where improvements are needed.

---

## Purpose of Finance Analytics

The Finance Analytics section focuses on providing a clear and detailed picture of Atliq Hardware Technologies' financial health through:

- Profit and Loss statements, helping to track revenue and costs across different markets  
- Time-based financial trends, providing insights into financial performance across months and fiscal years  

These reports are essential for decision-makers to monitor financial performance and make informed budgeting and resource allocation decisions.

---

## Workflow Breakdown

### Data Loading
- Imported five CSV files from Atliq Hardware Technologies into Power Query.

### Data Cleaning
- Removed duplicates, unnecessary columns, and standardized formats in Power Query.

### Data Modeling
- Created relationships between tables in the Data Model.
- Added a **Dim Date** table and connected tables for accurate reporting.

### Data Analysis
- Used Power Pivot and DAX to calculate key metrics such as:
  - Total revenue  
  - Market performance  
  - Target vs. actual sales  

### Report Creation
- **Customer Performance Report**: Analyzed customer behavior and sales contributions  
- **Market Performance Report**: Compared sales performance to targets  
- **P&L Reports**: Financial insights segmented by:
  - Market  
  - Month  
  - Fiscal Year  

---

## Role of Reports

- **Customer Performance Report**  
  Helps stakeholders focus on customer-specific strategies by identifying high-value customers and tracking purchasing behavior.

- **Market Performance Report**  
  Enables monitoring of market success and sales target achievement across regions and segments.

- **P&L Statements**  
  Crucial for financial planning and control—these track profitability by market, month, and fiscal year.

---

## Documentation

Check out all the created reports attached to this repository:

- ## Documentation

- [Customer Performance Report](https://github.com/GayathriDollani/Sales-Finance-Dashboard/blob/main/Customer_Performance_Report.pdf?raw=true)
- [Market Performance Report](https://github.com/GayathriDollani/Sales-Finance-Dashboard/blob/main/Market_Performance_Report.pdf?raw=true)
- [Market Performance Report](#)
- [P&L Statement By Market Report](#)
- [P&L Statement By Year Report](#)
- [P&L Statement By Month Report](#)

> _Replace the `#` in links above with actual file paths or anchor links if available._

## References

This project is part of a guided learning experience from the **Codebasics** website, under the course titled **"Excel: Mother of Intelligence."**  
It utilizes real-world business data from Atliq Hardware Technologies, focusing on sales and finance analytics.  
For more details on the course, visit the [Codebasics website](https://www.codebasics.io/).

