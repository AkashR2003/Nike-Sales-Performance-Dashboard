
# Nike Sales Performance Dashboard

## Project Overview

This project focuses on analyzing Nike sales performance using Power BI. The dashboard provides insights into revenue, profit, product performance, customer segments, sales channels, and regional trends.

The goal of this project was to transform raw sales data into meaningful business insights through data cleaning, modeling, DAX calculations, and interactive visualizations.

---

## Dashboard Preview

(Add your dashboard screenshot here)

---

## Key Metrics

* Total Revenue: 687.18K
* Total Profit: 3.44M
* Total Units Sold: 1.88K
* Profit Margin: 5.01%

---

## Dashboard Features

### Executive KPIs

* Total Revenue
* Total Profit
* Total Units Sold
* Profit Margin %

### Sales Analysis

* Revenue by Region
* Revenue by Product Line
* Revenue by Gender Category
* Revenue by Sales Channel
* Monthly Revenue Trend

### Profitability Analysis

* Profit by Product Line
* Product-Level Performance Analysis

### Interactive Features

* Dynamic filtering
* Drill-down analysis
* Cross-filtering visuals

---

## Data Cleaning & Transformation

The dataset was cleaned using Power Query:

* Handled missing values
* Standardized region names
* Corrected data types
* Created Date Table for time intelligence analysis

---

## Data Modeling

Created relationships between:

* Fact Sales Table
* Date Dimension Table

Implemented a star-schema approach for efficient reporting.

---

## DAX Measures Used

### Total Revenue

```DAX
Total Revenue =
SUM(Nike_Sales_Uncleaned[Revenue])
```

### Total Profit

```DAX
Total Profit =
SUM(Nike_Sales_Uncleaned[Profit])
```

### Total Units Sold

```DAX
Total Units Sold =
SUM(Nike_Sales_Uncleaned[Units_Sold])
```

### Profit Margin %

```DAX
Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Revenue]
)
```

---

## Tools & Technologies

* Power BI
* Power Query
* DAX
* Data Modeling
* Data Cleaning
* Data Visualization
* Business Intelligence

---

## Key Insights

* Kolkata generated the highest revenue among all regions.
* Training products delivered the highest profit contribution.
* Retail sales outperformed online sales.
* Customer segments showed different revenue contribution patterns.
* Monthly sales trends highlighted seasonal fluctuations.

---

## Skills Demonstrated

* Data Analysis
* Data Visualization
* Business Intelligence
* Dashboard Development
* Power BI
* Power Query
* DAX
* Reporting & Insights

---

## Author

Akash R

LinkedIn: Add your LinkedIn profile here
GitHub: Add your GitHub profile here
