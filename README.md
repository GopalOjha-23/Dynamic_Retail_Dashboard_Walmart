# Dynamic_Retail_Dashboard_Walmart

A dynamic retail dashboard that provides actionable insights into key performance metrics across sales, profitability, and customer segmentation.

---

## 🚀 Overview

This dashboard visualizes comprehensive retail data to help businesses make informed decisions. It tracks essential KPIs, identifies trends, and highlights opportunities for growth and optimization.

---

## 🚀 Key Features

Dynamic and interactive charts & graphs.

Real-time filters for time period, product category, and geography.

Easy-to-understand visuals optimized for decision-makers.

Fully automated calculations of KPIs for up-to-date metrics.

---

## ✅ Problem Statements Solved 

The dynamic retail dashboard answers several important business questions, providing in-depth insights into key performance areas:

1. **KPIs**
   - Total Sales
   - Total Profit
   - Quantity Sold
   - Number of Orders
   - Profit Margin

2. **Sales and Profit Analysis**
   - Understand overall sales and profitability dynamics.

3. **Category-wise Profit**
   - Analyze profit contribution by product category.

4. **Segment-wise Sales Share %**
   - Breakdown of sales by customer segment.

5. **Sales by Country**
   - Assess sales performance across countries or regions.

6. **Top 5 Subcategories**
   - Identify the best-performing subcategories based on sales.

7. **Bottom 5 Subcategories**
   - Highlight the weakest subcategories needing attention.

8. **Yearly Sales Trend**
   - Visualize sales evolution and detect seasonal trends.

---

## Solutions With Steps

### 1)KPIs – Total Sales, Total Profit, Quantity, No. of Orders, Profit Margin

✅ Steps:

1. Go to your visualization tool’s data view.
2. Create calculated measures or fields for:
3. Total Sales = SUM(Sales)
4. Total Profit = SUM(Profit)
5. Quantity = SUM(Quantity)
6. No. of Orders = DISTINCTCOUNT(Order ID)
7. Profit Margin = DIVIDE(SUM(Profit), SUM(Sales))
![image](https://github.com/user-attachments/assets/fcb55512-549f-4c11-9c51-bc02cfc300e4)

### 2) Sales and Profit Analysis – Overall Sales & Profitability
✅ Steps:

1. Create a Pivot Table with Order Date groped by Year and Month.
2. Add Sales and Profit as values.
3. Create Scatter Chart to display trends for sales and profit

![image](https://github.com/user-attachments/assets/42e37841-9963-4cd1-a821-cf7b8a05b7e4)

### 📸 3) Category-wise Profit – Breakdown by Product Category
✅ Steps:

1. Create a Pivot Table using Ccategory as rows and profit as values.
2. Sort the table in descending order of Profit
3. Create a Pie-Chart to visualize category-wise profit 
4. Add slicers for interactivity.

![image](https://github.com/user-attachments/assets/c67c3c92-e104-4a45-b7b6-afea360ebe3a)


📸 4) Segment-wise Sales Share % – Sales by Customer Segment
✅ Steps:

1. Create a Pivot Table with Segment as rows and Sales as values
2. Calculate percentage share using =Sales/Total Sales * 100
3. Create Donut Chart to display the Sales share
4. Add labels to show percentage values dynamically

![image](https://github.com/user-attachments/assets/3d327bdc-d70a-4ce1-8f00-e1bb002d3216)

   
📸 5) Sales by Country – Sales Performance by Geography
✅ Steps:

1. Add a Map visual (filled map or bubble map).
2. Drag Country to the location field.
3. Drag Sales to the size or color field.
4. Configure tooltips to show detailed info when hovering over a country.

![image](https://github.com/user-attachments/assets/00a4a5cd-d611-4014-b8a9-d558f0e7d552)


📸 6) Top 5 Subcategories – Best Performers
✅ Steps:

1. Create a Pivot Table with Sub-Category as rows and sales as Values.
2. Sort Table in descending order.
3. Filter to display the top 5 Sub-Categories.
4. Use a Column chart to visualize results.

![image](https://github.com/user-attachments/assets/f53cd5c5-ea85-4c3f-850f-9c3795b752a1)


📸 7) Bottom 5 Subcategories – Weakest Performers
✅ Steps:

1. Duplicate the previous Column chart. (I used a Horizontal Column Chart)
2. Sort ascending by Sales.
3. Use Top N filter with bottom 5 or manually select lowest performers.

![image](https://github.com/user-attachments/assets/2e5cae44-5c7b-4fc8-963d-1645b6eb888c)


📸 8) Yearly Sales Trend – How Sales Evolve Over Time
✅ Steps:

1. Create a Pivot Table with Year as Rows and Sales in the columns an values.
2. Extract year from Order Date by creating a calculated column/field.
3. Add a Line Chart.

![image](https://github.com/user-attachments/assets/757e7f05-eb1c-449a-8371-8c07075738be)



## 🎨 Features

- Dynamic, interactive charts and graphs.
- Real-time filters for flexible analysis by time, category, or geography.
- Automated KPI calculations for up-to-date metrics.
- User-friendly visuals optimized for business decision-makers.


---

## How it Helps
This dashboard empowers retail stakeholders to:

Gain instant visibility into performance across categories, segments, and regions.

Identify growth opportunities and address underperformance quickly.

Make data-driven decisions to optimize product strategy and marketing.



