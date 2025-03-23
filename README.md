# Superstore Sales Data Analysis and Sales Forecasting
## Superstore Sales Analysis Report
### Objective
This report analyzes the Superstore Sales dataset using Power BI. The goal is to discover key insights and actionable recommendations. This will drive better decisions regarding sales performance, profitability, and regional trends.
Superstore Sales Dataset Overview
### 🛒 1. Order Details:
•	Order ID: Unique identifier for each order
•	Order Date: Date when the order was placed
•	Ship Date: Date when the order was shipped
### 👥 2. Customer Details:
•	Customer Name: Name of the customer
•	Customer Segment: Segment classification (e.g., Consumer, Corporate)
### 📦 3. Product Details:
•	Category: High-level product category (e.g., Furniture, Technology)
•	Sub-Category: Detailed classification within a category (e.g., Chairs, Phones)
•	Product Name: Name/description of the product
### 💰 4. Sales Data:
•	Sales Amount: Total sales value of the order
•	Profit: Profit earned from the order
•	Discount: Discount applied to the order
•	Quantity: Number of units sold
### 🌍 5. Geography:
•	Region: Geographical region (e.g., East, West)
•	State: State where the order was shipped


## Data Cleaning & Preparation

### Data Loading
The Superstore Sales dataset was imported into Power BI.
#### •	Loaded the dataset into Power BI and ensured correct data types for each field.
•	Handled missing values: Removed any incomplete records affecting analysis.
•	Resolved duplicate entries to ensure data accuracy.
#### •	Created new calculated columns:
o	Order Processing Time = Ship Date - Order Date
o	Revenue = ([Sales Amount]-([Sales Amount]*[Discount]))*[Quantity]
•	Standardized category names for consistency.
#### Data Types
Verified data types to ensure accurate analysis.
#### Missing Values
Incomplete records were removed to prevent skewing results.
#### Data Transformation
Standardized data formats for consistency.

## Dashboard Overview & Key Visuals

 ### KPI Cards:
•	Total Sales: 25,30,65,000
•	Total Profit: 5,06,65,000
•	Total Quantity Sold: 5,49,000units

 ### Monthly Sales Trends (Line Chart):
•	Seasonal patterns observed, with the highest sales in Q4, likely due to holiday shopping trends.
 Profit Distribution Across Regions (Map):
•	The Central Region contributed the most to profit, while the West Region had declining profits.

 ### Product Performance (Bar Chart):
•	Best-Selling Products: Sofas
•	Least Profitable Products: Chairs

 ### Impact of Discount on Profitability (Scatter Plot):
•	Higher discounts often led to lower profit margins, suggesting a need to re-evaluate discounting strategies.
________________________________________
## Business Insights & Recommendations

### Key Insights:
High sales during Q4 indicate an opportunity for seasonal promotions. Certain regions show low profitability, requiring a review of pricing and marketing strategies. Some products contribute high sales but low profits, requiring better margin control. Heavy discounts negatively impact profitability; optimizing pricing strategies is necessary.

## Business Recommendations:
Optimize discount strategies to improve profit margins. Focus marketing efforts on high-performing regions and underperforming categories. Increase stock for top-selling products to avoid stockouts and maximize revenue. ** Analyze shipping times to improve customer satisfaction and reduce delivery delays.

## Conclusion
The Power BI dashboard successfully highlighted key insights into sales, profits, and regional performance. The recommended strategies can help boost profitability, optimize inventory, and improve marketing efforts. Further analysis of customer behavior and order trends can enhance business decisions.


## PowerBI Rport:
![Screenshot 2025-03-23 140403](https://github.com/user-attachments/assets/5de805a5-abc0-40d7-adca-90ab531e13cc)
![Screenshot 2025-03-23 140500](https://github.com/user-attachments/assets/d0f224f4-2438-41d7-8ee2-5a5578e453d9)
















