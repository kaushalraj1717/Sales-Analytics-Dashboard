
# 📊 Sales Analytics Dashboard — Power BI

## Project Overview

This project presents an interactive **Sales Analytics Dashboard** developed using **Microsoft Power BI**.  
The dashboard provides insights into sales performance, profit trends, product performance, and customer behavior over time.

It enables business users to monitor key performance indicators (KPIs) and make data-driven decisions using interactive visuals and filters.

The dashboard analyzes sales data from **2020 to 2024**, including metrics like:

- Total Sales  
- Profit  
- Quantity Sold  
- Number of Orders  

---

## Objectives

- Analyze overall sales and profit performance  
- Identify top and bottom performing products  
- Monitor sales trends over time  
- Evaluate the effect of discounts and promotions  
- Support business decision-making with data visualization  

---

## Dashboard Features

### 1. Sales Overview

- Total Number of Orders KPI  
- Profit vs Net Sales scatter plot  
- Sales Trends by Period (2020–2024)  

### 2. Product Performance Analysis

- Top 5 Products by Sales  
- Bottom 5 Products by Sales  
- Top 5 Products by Profit  
- Top and Bottom Products by Quantity  

### 3. Comparative Analysis

- Sales Comparison (Sales 1 vs Sales 2)  
- Profit Comparison (Profit 1 vs Profit 2)  
- Quantity Sold Comparison  

### 4. Interactive Filters

- Date Filter  
- Customer Filter  
- Product Filter  
- Promotion Filter  

---

## Data Model

This project follows a **Star Schema** data model.

### Fact Table

- CustomerID  
- OrderID  
- ProductID  
- PromotionID  
- Date  
- Discount  
- Discount Percentage  
- Net Sales  
- Price Per Unit  
- Profit  
- Quantity  

### Dimension Tables

#### Dim Customers

- Customer ID  
- Customer Name  
- City  
- State  
- Email  
- Phone Number  

#### Dim Product

- Product ID  
- Product Name  
- Product Line  
- Price Per Unit  

#### Dim Promotion

- Promotion ID  
- Promotion Name  
- Discount Percentage  
- Promotion Type  

#### Date Tables

- Date Table 1  
- Date Table 2  

---

## Tools & Technologies

- Microsoft Power BI  
- Power Query  
- DAX (Data Analysis Expressions)  
- Data Modeling  
- Data Visualization  

---

## Dataset

The dataset contains transactional sales records including:

- Customer information  
- Product details  
- Sales transactions  
- Discounts and promotions  
- Profit and revenue metrics  
- Time-based sales data  

---

## Key Insights

- Identified top-performing products by sales and profit  
- Observed sales growth patterns across multiple years  
- Analyzed the relationship between profit and net sales  
- Evaluated the impact of promotions on sales performance  

---

## How to Run the Project

1. Download or clone the repository  
2. Open the `.pbix` file in **Power BI Desktop**  
3. Click **Refresh** to update the data (if needed)  
4. Use filters and visuals to explore insights  

---

## Project Structure

Sales-Analytics-Dashboard/
│
├── Sales_Dashboard.pbix  
├── Dataset/  
│   ├── Fact_Table.xlsx  
│   ├── Dim_Customers.xlsx  
│   ├── Dim_Product.xlsx  
│   ├── Dim_Promotion.xlsx  
│
├── Screenshots/  
│   ├── Overview.png  
│   ├── Top_Bottom_Analysis.png  
│   ├── Sales_Trends.png  
│
└── README.md  


---

## ⭐ Project Type

Portfolio Project — Power BI Dashboard  

---


