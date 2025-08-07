💡 Key Visuals in the Dashboard:

KPI Card - Total Sales
 Sales Performance (Line Chart)
 Visualizes sales trends over the years (2020, 2021, 2022).
 Clearly shows exponential growth.

Total Sales by Continent (Bar Chart)
 Sales split by region:
 North America: $9.0M
 Australia: $5.1M
 Europe: $3.2M

Total Margin% by Product Category (Bar Chart)
 Compares margin across:
  Accessories
  Bikes
  Clothing

Filters Panel
 Continent: View regional-specific data.
 Year: Drill into a specific time period.

🧭 How to Navigate the Report

Use Filters on the Right:
 Select a Continent to view data from a specific region.
 Choose a Year to focus on yearly performance.

Hover on Visuals:
 Tooltips show exact values and margins.
 Use hover actions to explore trends in more detail.

Interactive Visuals:
 Click on bars in the chart to cross-filter other visuals and drill through.
 Useful for drilling down into specific categories or regions.
 

## 📌 Project Overview

As part of the course, I completed a **capstone Power BI project** simulating a real-world analytics scenario for a retail company. This involved building an interactive, end-to-end BI solution using multiple datasets.

### 🧾 Project Scenario
Analyze sales performance and customer behavior for a fictional retail company to support business decision-making.

### 🧱 Key Steps

#### 1. Data Import & Transformation (Power Query)
- Loaded datasets: Sales, Customers, Products, Regions, Calendar
- Cleaned data: removed nulls, standardized columns
- Merged tables using joins
- Created new calculated columns (e.g., Total Revenue)

#### 2. Data Modeling
- Created a star schema model
- Built relationships between fact and dimension tables
- Added hierarchies (Year > Quarter > Month)

#### 3. DAX Calculations
- `Total Sales`, `Total Quantity`, `Profit Margin %`, `YoY Growth`
- Used functions like `CALCULATE`, `SAMEPERIODLASTYEAR`, `DATESYTD`, `FILTER`

#### 4. Report Design
- Pages: Overview, Sales Trends, Regional Insights, Customer Analysis, Product Analysis
- Visuals: KPIs, Line Charts, Maps, Pie Charts, Matrix Tables
- Added slicers, tooltips, drill-throughs, bookmarks, and buttons
  
