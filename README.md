# 🛒 E-Commerce Sales Dashboard | Microsoft Excel

## 🎯 Project Objective

The objective of this dashboard is to analyze e-commerce sales performance and provide interactive insights into sales trends, profitability, regional performance, product categories, customer purchases, discount impact, and payment preferences to support data-driven business decisions.

---

## 📊 Dataset Description

The dataset contains 5,000 e-commerce sales transaction records. Each row represents an order and includes customer, product, sales, profit, discount, region, city, and payment information.

### Dataset Columns

| **Column** | **Description** |
|---|---|
| Order ID | Unique identifier for each order |
| Order Date | Date when the order was placed |
| Year | Year extracted from Order Date |
| Month | Month extracted from Order Date |
| Customer Name | Name of the customer |
| Region | Sales region (East, West, North, South) |
| City | City associated with the order |
| Category | Main product category |
| Sub-Category | Specific product sub-category |
| Product Name | Name of the product purchased |
| Quantity | Number of units purchased |
| Unit Price | Price per unit |
| Sales | Total sales amount before discount |
| Discount | Discount amount applied to the order |
| Profit | Profit earned from the order |
| Payment Mode | Payment method used |
| Net Revenue | Revenue after deducting the discount |

### Dataset Overview

- **Total Records:** 5,000
- **Total Columns:** 17
- **Date Range:** October 2023 – October 2025
- **Product Categories:** 10
- **Sales Regions:** 4
- **Payment Modes:** 5

---

## 🧮 Calculated Columns

- **Year** – Extracted from Order Date to support yearly analysis.
- **Month** – Extracted from Order Date for monthly sales analysis.
- **Discount** – Represents the discount amount applied to each order.
- **Net Revenue** – Calculated by subtracting Discount from Sales.

**Formula:**

Net Revenue = Sales − Discount

---

## 📈 Dashboard Features

### KPI Cards

- Total Orders
- Total Sales
- Total Net Revenue
- Total Profit
- Total Quantity Sold
- Average Order Value
- Profit Margin (%)

### Charts

- 📈 Monthly Sales Trend
- 📊 Profit by Category
- 📊 Sales by Region
- 🏆 Top 10 Products by Profit
- 📊 Sales and Profit by City
- 🥧 Sales Distribution by Payment Mode
- 📉 Discount Impact on Profitability

### Interactive Filters

- Year
- Month
- Region
- Category
- Sub-Category
- Payment Mode

---

## 🔍 Key Insights

### Overall Business Performance

- **Total Sales:** ₹593.17M (₹59.32 Crore)
- **Total Net Revenue:** ₹533.85M (₹53.39 Crore)
- **Total Profit:** ₹79.71M (₹7.97 Crore)
- **Total Orders:** 5,000
- **Total Quantity Sold:** 14,963 units
- **Average Order Value:** ₹118,634
- **Overall Profit Margin:** 13.44%

### Regional Performance

- **North** is the highest-performing region by sales, generating approximately ₹160.30M.
- **South** records the lowest sales among the four regions, at approximately ₹136.86M.
- North also generates the highest total profit, while South generates the lowest.
- The results suggest an opportunity to investigate sales growth and product demand in the South region.

### Category Performance

- **Furniture** generates the highest profit, at approximately ₹8.69M.
- **Home Decor** records the highest sales, at approximately ₹63.69M.
- **Groceries** generates the lowest profit, at approximately ₹7.08M.
- The difference between the highest- and lowest-profit categories suggests that category-level profitability should be considered alongside sales.

### Product Performance

- **Sofa** is the highest-selling sub-category by sales, generating approximately ₹16.99M.
- **Lamp** ranks second in sub-category sales, at approximately ₹16.46M.
- Product-level profit analysis can help identify products that contribute most to overall profitability.
- The Top 10 Products by Profit chart can help prioritize products that generate stronger financial returns.

### Payment Mode Analysis

- **Net Banking** records the highest sales, at approximately ₹123.79M.
- **COD** follows with approximately ₹121.12M in sales.
- UPI records approximately ₹113.74M in sales.
- The five payment modes have relatively similar sales contributions, so no single payment method dominates the dataset.

### Monthly Sales Trend

- **May** records the highest total sales when records are grouped by month name, at approximately ₹56.12M.
- **February** records the lowest total sales, at approximately ₹43.93M.
- Sales vary across the months, creating opportunities to investigate seasonal demand and plan promotions.
- Since the dataset covers multiple years and incomplete calendar years, monthly comparisons should be interpreted carefully.

### City Performance

- **Bangalore** records the highest sales among the listed cities, at approximately ₹33.23M.
- **Thiruvananthapuram** records the lowest sales, at approximately ₹22.57M.
- Bangalore also generates substantial profit, while city-level profit margins can help identify locations with stronger profitability relative to sales.
- Further analysis can help determine whether lower-sales cities need different product selections or marketing strategies.

### Discount and Profitability Analysis

- **Total Discount:** Approximately ₹59.32M.
- Discounts represent 10% of total sales in this dataset.
- Comparing profit margins across different discount levels can help evaluate whether higher discounts are associated with lower profitability.
- The business should review discount effectiveness before increasing promotional discounts.

---

## 📝 Conclusion

The E-Commerce Sales Dashboard provides a consolidated view of sales performance, profitability, regional performance, product categories, payment preferences, and discount analysis. The analysis shows that the dataset contains **₹59.32 crore in sales, ₹53.39 crore in net revenue, and ₹7.97 crore in profit**, with an overall profit margin of **13.44%**. North is the leading region by sales, Furniture generates the highest category-level profit, and Home Decor records the highest category-level sales. Sofa is the leading sub-category by sales, while Net Banking records the highest sales among the payment modes.
The analysis also identifies differences in monthly sales and city-level performance, providing opportunities for further investigation into demand, profitability, and discount effectiveness. Overall, the dashboard demonstrates how Microsoft Excel can transform raw sales data into meaningful business insights and support data-driven decision-making.

---
