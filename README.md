# Superstore Sales Analysis using SQL

## Project Overview

This project focuses on analyzing the Superstore dataset using SQL. The objective is to explore the dataset, apply filters, perform aggregations, analyze business use cases, and validate data quality. The analysis helps understand sales performance, customer behavior, product trends, and regional performance.

---

## Objective

To analyze sales data using SQL by performing:

* Data loading and validation
* Table exploration
* Filtering using WHERE clauses
* Aggregations using GROUP BY
* Sorting and ranking results
* Solving business use cases
* Data quality validation

---

## Dataset Information

Dataset: Sample Superstore Dataset

The dataset contains information related to:

* Orders
* Customers
* Products
* Sales
* Quantity
* Discounts
* Profit
* Regions and States

The dataset consists of 21 columns including Order ID, Customer Name, Product Name, Sales, Quantity, Discount, and Profit.

---

## Tools Used

* MySQL Workbench
* SQL
* Microsoft Excel (for CSV conversion)

---

## Data Import Process

### Step 1: Download Dataset

Downloaded the Superstore dataset in Excel format (.xlsx).

### Step 2: Convert Excel to CSV

Converted the Excel file into CSV format for easy import into MySQL.

### Step 3: Create Database

```sql
CREATE DATABASE shopease_db;
USE shopease_db;
```

### Step 4: Create Table

Created the table using appropriate column names and data types.

### Step 5: Import Data

Imported the CSV file using MySQL Workbench Table Data Import Wizard.

### Step 6: Verify Import

Verified successful import using row count and sample data queries.

---

# Step 1: Explore Table

### Activities Performed

* Viewed table schema
* Checked sample records
* Counted total rows
* Identified unique regions
* Identified unique categories
* Identified unique customer segments
* Verified date range
* Counted unique customers, products, and orders

### Key Findings

* Dataset contains customer, product, and sales information.
* Multiple regions and customer segments are present.
* Data spans multiple years, enabling trend analysis.
* One order may contain multiple products.

---

# Step 2: Apply WHERE Filters

### Filters Used

#### Region Filters

* West Region Orders
* Orders Not from South Region
* East and Central Region Orders

#### Category Filters

* Technology Orders
* Non-Furniture Orders
* Selected Sub-Categories

#### Date Filters

* Orders after 2016
* Orders from 2017
* Orders in November

#### Sales Filters

* High Value Orders
* Low Value Orders
* Orders with Losses

#### Combined Filters

* West + Technology + Sales > 500
* East + Furniture + 2017

### Key Findings

* Sales performance differs across regions.
* Technology products generate higher-value transactions.
* November shows strong customer activity.
* Some high-sales orders still generate losses.

---

# Step 3: GROUP BY Aggregations

### Aggregations Performed

* Total Sales by Region
* Quantity Sold by Category
* Average Sales by Category
* Sales and Profit by Sub-Category
* Sales by Region and Category
* Orders by State

### Key Findings

* Different regions contribute differently to revenue.
* Product categories vary in sales volume and profitability.
* Some sub-categories perform significantly better than others.
* Sales and profit should be analyzed together for better business understanding.

---

# Step 4: Sorting and Limiting Results

### Analysis Performed

* Top Products by Sales
* Bottom Products by Sales
* Top Categories
* Top Profit-Making Sub-Categories
* Loss-Making Sub-Categories
* Top States by Sales
* Most Ordered Products

### Key Findings

* A small number of products contribute significantly to revenue.
* Some products generate sales but very little profit.
* Certain states contribute a large portion of total business revenue.

---

# Step 5: Business Use Cases

### Business Questions Solved

* Monthly Sales Trend
* Best Sales Month per Year
* Duplicate Order Analysis
* Duplicate Customer Orders
* Top Customers by Orders
* Loyal Customers
* Quarterly Sales Trends
* Customer Engagement Analysis

### Key Findings

* Sales vary throughout the year.
* Certain months consistently perform better than others.
* Loyal customers contribute significantly to business activity.
* Duplicate Order IDs are expected because a single order can contain multiple products.

---

# Step 6: Data Validation

### Validation Checks Performed

* Total Row Count
* Invalid Sales Values
* Negative Quantity Check
* Loss-Making Orders
* Numeric Column Validation
* Region and Category Coverage

### Key Findings

* Dataset was imported successfully.
* No major data quality issues were identified.
* Sales, quantity, discount, and profit values were within expected ranges.
* All major regions and categories are represented in the dataset.

---

# Overall Conclusion

The Superstore dataset was successfully analyzed using SQL. Various filtering, aggregation, sorting, and validation techniques were applied to gain insights into sales performance, customer behavior, and product profitability.

The analysis showed that sales trends vary across regions, categories, and time periods. Technology products contribute significantly to revenue, while customer purchasing patterns reveal opportunities for improving retention and business growth.

This project demonstrates practical SQL skills including data exploration, filtering, aggregation, business analysis, and data validation, making it a valuable exercise in data analytics and business intelligence.

---

## Files Included

* SQL Script
* Query Outputs / Screenshots
* README.md
* Dataset (CSV)

## Author

Celebal Technologies Internship Assignment
SQL Data Analysis Project
