# Superstore Sales Data Analysis

## Project Overview

This project analyzes Superstore sales data using Python and SQL to identify
sales trends, profitability patterns, regional performance, customer segments,
top-performing products, loss-making products, and the relationship between
discounts and profit.

The project demonstrates practical data analysis skills that can be applied
to real-world business datasets.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- SQLite
- Jupyter Notebook

## Dataset

The dataset contains 9,994 sales records with information about:

- Orders
- Customers
- Products
- Categories
- Regions
- Sales
- Quantity
- Discounts
- Profit
- Order and shipping dates

## Data Cleaning

The following preprocessing steps were performed:

- Checked missing values
- Checked duplicate records
- Converted date columns to datetime format
- Created Year and Month features
- Created Year-Month feature
- Calculated shipping duration

## Key Business Metrics

| Metric | Value |
|---|---:|
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Total Orders | 5,009 |
| Total Customers | 793 |
| Total Quantity | 37,873 |
| Average Order Value | $458.61 |
| Profit Margin | 12.47% |

## Analysis Performed

### 1. Yearly Sales & Profit
Analyzed sales and profit trends from 2014 to 2017.

### 2. Category Analysis
Compared sales and profit across Technology, Furniture, and Office Supplies.

### 3. Regional Analysis
Analyzed sales and profit across West, East, Central, and South regions.

### 4. Product Analysis
Identified the top 10 products by sales and the top 10 loss-making products.

### 5. Customer Segment Analysis
Compared Consumer, Corporate, and Home Office segments.

### 6. Discount Analysis
Examined the relationship between discount levels and average profit.

## Key Findings

- Technology generated the highest sales and profit among the three categories.
- West generated the highest regional sales and profit.
- The Canon imageCLASS 2200 Advanced Copier was the highest-selling product.
- Several products generated significant losses despite having sales.
- Furniture generated relatively high sales but substantially lower profit than Technology and Office Supplies.
- Higher discount levels were generally associated with lower average profit in this dataset.

## Project Structure

```text
Superstore_Sales_Analysis/
│
├── data/
│   ├── Sample - Superstore.csv
│   └── superstore.db
│
├── notebook/
│   └── Superstore_Sales_Analysis.ipynb
│
├── figures/
│   ├── yearly_sales_profit.png
│   ├── sales_by_category.png
│   ├── profit_by_category.png
│   ├── sales_by_region.png
│   ├── profit_by_region.png
│   ├── top_10_products.png
│   ├── loss_making_products.png
│   └── discount_vs_profit.png
│
└── README.md