# Corporate Actions Analytics Dashboard

This project is an end-to-end data analytics project built using SQL, Microsoft Excel, Power Query, and Power BI.

The project analyzes 250 corporate action events across the USA and Canada from April 2025 to March 2026. The goal is to understand corporate action trends, perform data validation, and create interactive dashboards for reporting.

---

## Project Overview

This project covers the complete analytics workflow:

- Data preparation using Excel
- SQL analysis and reusable SQL Views
- Data transformation using Power Query
- Interactive dashboards in Excel
- Data modeling and dashboard creation in Power BI
- Data quality validation

---

## Tools Used

| Tool | Purpose |
|------|----------|
| MySQL Workbench | SQL queries, Views and data analysis |
| Microsoft Excel | Pivot Tables, Pivot Charts, KPI Dashboard |
| Power Query | Data cleaning and transformation |
| Power BI | Data Model, DAX Measures and Dashboards |
| GitHub | Project documentation |

---

## Dataset

The sample dataset contains:

- 250 Corporate Action Events
- USA and Canada markets
- April 2025 – March 2026

Fields include:

- Announcement Date
- Company Name
- Country
- Exchange
- Event Type
- Security ID
- Identifier Type
- Announcement Source
- Sector
- Market Cap Category
- Event Status

---

## SQL Analysis

SQL was used to analyze the dataset and create reusable Views.

Topics covered:

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- COUNT
- COUNT DISTINCT
- CREATE VIEW
- DATE_FORMAT
- Aggregate Functions

Sample SQL analysis includes:

- Total Events
- Company Count
- Country Count
- Sector Count
- Event Type Count
- Monthly Trend
- Market Cap Analysis

SQL script is available in the **sql** folder.

---

## Excel Dashboard

Two dashboards were created in Excel.

### 1. KPI Dashboard

Features:

- KPI Cards
- Monthly Trend
- Country Analysis
- Sector Analysis
- Event Type Analysis
- Market Cap Analysis
- Interactive Slicers

### 2. SQL Dashboard

Created using:

- SQL Views
- Power Query
- Excel Data Model
- Pivot Tables
- Pivot Charts
- Slicers

---

## Power BI Dashboard

The Power BI report contains three pages.

### Executive Overview

Shows:

- Total Events
- Unique Companies
- Top Country
- Top Sector
- Top Event Type
- Monthly Trend
- Market Cap Distribution
- Country Distribution

---

### Corporate Actions Analysis

Shows:

- Event Details Table
- Event Type by Country
- Announcement Source Analysis
- Event Status by Country
- Identifier Type Analysis
- Interactive Filters

---

### Data Quality & Operations Check

Shows:

- Blank Security IDs
- Blank Event Types
- Blank Sources
- Validation Table
- Event Status Summary
- Source Validation

---

## Power BI Features Used

- Power Query
- Data Model
- Star Schema
- Relationships
- Dimension Tables
- Fact Table
- DAX Measures
- Cards
- Tables
- Matrix
- Bar Charts
- Line Chart
- Slicers

---

## Key Insights

- Total Corporate Action Events: **250**
- Canada recorded **131** events.
- USA recorded **119** events.
- Consumer Goods was the most active sector.
- Tender Offer and Rights Issue were the most common event types.
- Large Cap companies recorded the highest number of events.
- Regulatory Filing was the most common announcement source.

---

## Repository Structure

```
corporate-actions-dashboard/

│── README.md

│── LICENSE

│

├── data/

│     corporate_actions_sample_data.xlsx

│

├── sql/

│     corporate_actions_queries.sql

│

├── excel/

│     Corporate_Actions_KPI_Dashboard.xlsx

│     Corporate_Actions_SQL_Dashboard.xlsx

│

├── powerbi/

│     Corporate_Actions.pbix

│

└── screenshots/

      01_excel_dashboard.png

      02_sql_dashboard.png

      03_powerbi_executive_overview.png

      04_powerbi_analysis.png

      05_powerbi_data_quality.png

      06_power_query.png

      07_data_model.png
```

---

## Screenshots

### Excel KPI Dashboard

![Excel Dashboard](screenshots/01_excel_dashboard.png)

---

### SQL Dashboard

![SQL Dashboard](screenshots/02_sql_dashboard.png)

---

### Power BI Executive Overview

![Executive Overview](screenshots/03_powerbi_executive_overview.png)

---

### Power BI Corporate Actions Analysis

![Corporate Actions Analysis](screenshots/04_powerbi_analysis.png)

---

### Power BI Data Quality & Operations Check

![Data Quality](screenshots/05_powerbi_data_quality.png)

---

### Power Query Transformations

![Power Query](screenshots/06_power_query.png)

---

### Power BI Data Model

![Data Model](screenshots/07_data_model.png)

---

## Learning Outcomes

Through this project, I practiced:

- SQL querying
- SQL Views
- Data aggregation
- Excel dashboards
- Pivot Tables
- Pivot Charts
- Power Query transformations
- Data modeling
- DAX measures
- Power BI dashboard development
- Data quality validation
- GitHub project documentation

---

## Author

**Jyothi Priya Garnepelli**

Reference Data Analyst | Capital Markets | SQL | Excel | Power BI

LinkedIn:
https://www.linkedin.com/in/jyothi-priya-garnepelli/

GitHub:
https://github.com/jyothigarnepelli23