# MIS 311 - Supermarket Sales Analysis

## Project Overview
This project analyzes supermarket sales data to identify sales patterns across product categories and cities. The goal is to use exploratory data analysis to generate business insights that can support decisions related to inventory planning, sales strategy, and location-based business performance.

## Dataset Description
The dataset contains supermarket transaction records. It includes sale ID, branch, city, customer type, product name, product category, quantity sold, and total price.

## Tools Used
- Microsoft Excel
- PivotTable
- Descriptive Statistics
- Data Visualization

## Data Cleaning
The original dataset contained 253 transaction records and 8 columns. Missing values were found in customer_type, product_category, and quantity. Since the number of affected rows was small compared to the total dataset, rows with missing values were removed to maintain the accuracy of the analysis.

Duplicate rows were also checked using Excel’s Remove Duplicates function. Three duplicate records were found and removed because duplicated sales transactions could overstate total revenue and quantity sold. After cleaning, the final dataset contained 239 records.

## Descriptive Statistics

After cleaning, the dataset contained 239 sales transactions. The total revenue was $30,362.94, with 2,576 units sold. The average transaction value was $127.04, while the median transaction value was $106.59, showing that some transactions were much larger than typical purchases.

### Overall Descriptive Statistics

| Metric | Value |
|---|---:|
| Number of Transactions | 239 |
| Total Revenue | $30,362.94 |
| Total Quantity Sold | 2,576 |
| Average Transaction Value | $127.04 |
| Median Transaction Value | $106.59 |
| Minimum Transaction Value | $2.18 |
| Maximum Transaction Value | $427.14 |

### Revenue by Product Category

| Product Category | Revenue |
|---|---:|
| Fruits | $7,450.12 |
| Beverages | $6,463.17 |
| Stationery | $6,255.25 |
| Household | $5,684.81 |
| Personal Care | $4,509.59 |

### Revenue by City

| City | Revenue | Transactions | Average Revenue per Transaction |
|---|---:|---:|---:|
| Chicago | $10,813.94 | 72 | $150.19 |
| New York | $10,613.69 | 90 | $117.93 |
| Los Angeles | $8,935.31 | 77 | $116.04 |

## Visualizations

### FIGURE 1. Revenue by Product Category
![Revenue by Product Category](Images/revenue_by_category.png)

### FIGURE 2. Revenue by City
![Revenue by City](Images/revenue_by_city.png)

## Key Insights

### Insight 1: Product Category Performance
Fruits generated the highest revenue at $7,450.12, accounting for approximately 24.5% of total sales revenue. This suggests that Fruits is the strongest product category in the supermarket and should receive strong inventory support to avoid stock shortages. In contrast, Personal Care generated the lowest revenue at $4,509.59, so the supermarket may need to review its promotion strategy, pricing, or product variety in this category.

### Insight 2: City Sales Performance
Chicago generated the highest revenue at $10,813.94, slightly higher than New York at $10,613.69 and Los Angeles at $8,935.31. Although New York had more transactions, Chicago produced higher total revenue, which suggests that customers in Chicago may have a higher average spending per transaction. The supermarket could study Chicago’s sales patterns to understand what drives stronger transaction value in that city.

## Conclusion
The analysis shows that supermarket sales performance varies by product category and city. Fruits was the top-performing product category, while Chicago generated the highest total revenue among the cities. These findings can help the supermarket improve inventory planning, product promotion, and city-based sales strategies.
