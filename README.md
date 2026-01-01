# AdventureWorks Sales Power BI Dashboard

## 📊 Project Overview
This Power BI dashboard delivers end-to-end business insights using the AdventureWorks dataset.  
It enables stakeholders to analyze sales performance, product trends, customer behavior, and regional performance through interactive and visually intuitive dashboards.

The project follows Power BI best practices including star schema data modeling, optimized DAX measures, and business-focused visual storytelling.

---

## 🧩 Business Problem
AdventureWorks leadership required a centralized reporting solution to:
- Monitor revenue, profit, and return trends in real time
- Identify top-performing and underperforming products
- Analyze customer purchasing behavior and segmentation
- Compare regional performance across global markets
- Support data-driven pricing and profitability decisions

---

## 📊 Dashboard Pages

### 1️⃣ Executive Dashboard
- Key KPIs: Total Revenue, Profit, Orders, Return Rate
- Revenue and order trends over time
- Category-wise order distribution
- Top products by revenue and return percentage

### 2️⃣ Product Detail Analysis
- Product-level performance vs targets
- Dynamic price simulation using What-If parameters
- Orders, revenue, profit, and return trend analysis
- Scenario-based profitability evaluation

### 3️⃣ Customer Detail Analysis
- Total and unique customer analysis
- Revenue per customer trends
- Customer segmentation by income and occupation
- Top customers contributing to overall revenue

### 4️⃣ Geographic Analysis
- Interactive map visualization of regional performance
- Sales distribution across North America, Europe, and Pacific
- Region-based filtering for focused analysis

---

## 🧱 Data Model
- Star schema design
- Fact table: Sales
- Dimension tables: Date, Product, Customer, Geography
- One-to-many relationships with single-direction filtering
- Optimized model for performance and scalability

---

## 🛠 Tools & Power BI Skills Demonstrated
- Power BI Desktop
- Power Query (Data Cleaning & Transformation)
- DAX (Measures, KPIs, Time Intelligence)
- Star Schema Data Modeling
- What-If Parameters
- Interactive Slicers, Drill-through & Cross-filtering
- Data Visualization & Visual Storytelling

---

## 🧮 Sample DAX Measures
```DAX
Total Revenue = SUM(Sales[Revenue])

Total Profit = SUM(Sales[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Revenue])

Total Orders = DISTINCTCOUNT(Sales[OrderID])

---

## 📸 Dashboard Preview

### Executive Dashboard
![Executive Dashboard][(https://github.com/user-attachments/assets/c66ef68b-4788-4c51-8133-3844e5b76890)](https://github.com/ssunidhi0115/powerbi-adventureworks-dashboard/blob/main/Exec%20Dashboard.png)

### Product Detail Analysis
![Product Detail][(https://github.com/user-attachments/assets/49ee303a-0432-4b29-82e4-ebdbc0f6bb05)](https://github.com/ssunidhi0115/powerbi-adventureworks-dashboard/blob/main/Product%20Detail.png)

### Customer Detail
![Customer Detail][(https://github.com/user-attachments/assets/8cd609ae-ae88-4c24-9ebb-b6c6fdd1c8f0)](https://github.com/ssunidhi0115/powerbi-adventureworks-dashboard/blob/main/Customer%20Detail.png)

### Geographic Analysis
![Geographic Analysis][(https://github.com/user-attachments/assets/d78f25ac-9f7c-401f-befb-2623e39ec0fe)](https://github.com/ssunidhi0115/powerbi-adventureworks-dashboard/blob/main/Map.png)

## 👤 Author
**Sunidhi Shukla**  
Power BI Developer | Data Analyst  
