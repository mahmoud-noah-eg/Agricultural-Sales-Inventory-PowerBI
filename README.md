# Agricultural-Sales-Inventory-PowerBI
Power BI dashboard analyzing agricultural sales, revenue trends, product performance, and inventory across 2022–2023.
# 🌾 Agricultural Sales & Inventory Performance Dashboard

## 📊 Project Overview

This project analyzes agricultural product sales and inventory performance from **2022 to 2023** using Microsoft Power BI.

The dashboard provides an interactive overview of revenue, sales volume, inventory levels, product performance, and category contributions. It helps identify top-performing products, track year-over-year changes, and understand the relationship between shipped, sold, and remaining quantities.

The goal is to transform raw agricultural sales data into actionable business insights through data modeling, DAX calculations, and interactive visualizations.

## 🖼️ Dashboard Preview

![Agricultural Sales & Inventory Performance Dashboard](AgricultureData%20Dashboard_MN.png)

## 🎯 Business Objectives

- Monitor overall revenue and sales performance.
- Compare business performance between 2022 and 2023.
- Identify the highest-revenue product categories and products.
- Analyze the relationship between shipped quantities, sold quantities, and remaining inventory.
- Evaluate sales efficiency using the sell-through rate.
- Provide insights that can support inventory planning and business decisions.

## 📁 Dataset Overview

The dataset contains agricultural product sales records covering the period from **January 2022 to December 2023**.

| Attribute | Description |
|---|---|
| Product | Product ID and product name |
| Category | Agricultural product category |
| Price per Kg | Price of each kilogram |
| Units Shipped | Quantity shipped in kilograms |
| Units Sold | Quantity sold in kilograms |
| Units On Hand | Remaining quantity in kilograms |
| Supplier | Product supplier |
| Farm Location | Recorded farm location |
| Sale Date | Date of the sales record |

**Dataset source:** [Agricultural Products Sales Data 2022–2023 — Kaggle](https://www.kaggle.com/datasets/kdstoys/agricultural-products-sales-data-2022-2023)

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Dashboard development and data visualization
- **Power Query** — Data inspection and preparation
- **DAX** — Measures, KPIs, and year-over-year calculations
- **Data Modeling** — Date table and time-based analysis

## 📌 Key Performance Indicators (KPIs)

The dashboard tracks the following metrics:

| KPI | Result |
|---|---:|
| Total Revenue | $413.58M |
| Total Units Shipped | 226.52M kg |
| Total Units Sold | 111.57M kg |
| Total Units On Hand | 114.96M kg |
| Average Price per Kg | $3.64 |
| Sell-Through Rate | 49.25% |
| Inventory Remaining Rate | 50.75% |

*These figures represent the overall dataset before applying dashboard filters.*

## 🔍 Key Business Insights

### 1. Revenue Performance

- Total revenue reached approximately **$413.58 million** across the two-year period.
- Revenue declined from **$209.49 million in 2022** to **$204.09 million in 2023**.
- This represents a year-over-year decrease of approximately **2.57%**.

### 2. Category Performance

- **Livestock** was the leading category, generating approximately **$184 million**, or **44.41%** of total revenue.
- Dairy contributed approximately **$99 million**, followed by Fruits at **$87 million**.
- Vegetables and Grains contributed smaller shares of total revenue.

### 3. Top-Performing Products

The leading products by revenue were:

1. **Lamb:** $69.96M
2. **Beef:** $60.39M
3. **Cheese:** $45.76M
4. **Pork:** $36.63M
5. **Butter:** $29.29M

These results highlight the importance of livestock and selected dairy products to overall revenue.

### 4. Sales and Inventory Performance

- The sell-through rate was approximately **49.25%**.
- The inventory remaining rate was approximately **50.75%**.
- Units sold decreased by approximately **0.66%** in 2023 compared with 2022.
- Units shipped decreased by approximately **2.56%**.
- Units on hand decreased by approximately **4.37%**.

The remaining inventory percentage suggests an opportunity to investigate stock movement, product-level demand, and inventory planning.

### 5. Average Price Analysis

- The average price per kilogram decreased from approximately **$3.71 in 2022** to **$3.58 in 2023**.
- This represents a year-over-year decrease of approximately **3.49%**.

Further analysis would be needed to determine how much of the revenue change is associated with pricing, sales volume, or changes in the product mix.

## 📈 Dashboard Features

- Interactive slicers for **Year, Category, Product, and Supplier**.
- KPI cards with year-over-year performance indicators.
- Monthly revenue trend covering 2022 and 2023.
- Revenue comparison across product categories.
- Top 10 products ranked by revenue.
- Sales and remaining inventory comparison for the top 10 products.
- Dark-themed dashboard layout designed for clear and accessible reporting.

## 💡 Business Recommendations

- **Review livestock performance:** Investigate demand and profitability for the highest-revenue livestock products.
- **Optimize inventory planning:** Examine products with relatively high remaining quantities and slower sales movement.
- **Monitor revenue trends:** Track monthly revenue and investigate periods of significant increases or decreases.
- **Evaluate pricing changes:** Assess whether price movements or product mix changes are affecting revenue.
- **Improve product-level reporting:** Use the interactive filters to identify differences between suppliers, categories, and products.

## ✅ Data Validation

The data quality checks performed on the dataset found:

- No missing values.
- No duplicate records.
- No negative prices or quantities.
- No records where sold quantities exceeded shipped quantities.
- The relationship `Units Shipped = Units Sold + Units On Hand` held across all records.

These checks support the consistency of the supplied dataset, although they do not independently verify the accuracy of the original business records.


## 👨‍💻 Author

**Mahmoud Noah**

- LinkedIn: www.linkedin.com/in/mahmoud-noah
- GitHub: https://github.com/mahmoud-noah-eg

This project demonstrates practical skills in business intelligence, data analysis, DAX, and interactive dashboard design using Microsoft Power BI.

If you find this project useful, feel free to ⭐ the repository.

