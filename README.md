# Sales & Revenue Analysis

## Overview
This project demonstrates a complete **sales and revenue analysis** using a simulated dataset.  
The goal is to replicate real-world business analytics tasks and prepare for data analytics internships.  

The analysis includes **data cleaning, exploration, and visualization**, along with actionable business insights.

---

## Dataset
- The dataset contains **863 sales orders** across multiple products, categories, regions, and sales representatives.  
- Key columns include:
  - `OrderID` – Unique order identifier  
  - `CustomerName` – Name of the customer  
  - `Product` – Product name  
  - `Category` – Product category  
  - `Quantity` – Units sold  
  - `PricePerUnit` – Price per unit in USD  
  - `Discount` – Discount applied (in %)  
  - `TotalAmount` – Total revenue after discount  
  - `OrderDate` – Date of the order  
  - `Region` – Region of the customer  
  - `SalesRep` – Responsible sales representative  

> The dataset includes intentionally messy data (missing values, typos, and inconsistencies) to simulate real-world scenarios.

---

## Steps Performed

1. **Data Cleaning**
   - Corrected typos in `Category` and `Product`
   - Filled missing `Quantity`, `PricePerUnit`, and `Discount`
   - Converted `OrderDate` to proper datetime
   - Recalculated `TotalAmount` after cleaning

2. **Exploratory Data Analysis**
   - Revenue by product and category
   - Top-performing products and sales reps
   - Revenue by region
   - Time-based analysis (daily, monthly trends)
   - Discount impact on quantity sold and revenue
   - Outlier detection (top orders by revenue)

3. **Visualizations**
   - Bar charts for revenue by category, product, region, and sales rep
   - Line chart for monthly revenue trend
   - Scatter plot for quantity vs revenue
   - Discount vs revenue chart

---

## Key Insights

- **Top Categories:** Electronics generate the highest revenue, followed by Clothing and Furniture.  
- **Top Products:** Desk, Monitor, and Chairs are the most profitable items.  
- **Regional Performance:** The West and North regions contribute the most revenue.  
- **Top Sales Reps:** Certain reps consistently outperform others in sales.  
- **Seasonality:** Revenue peaks during certain months and days, indicating seasonal demand trends.  
