#  E-commerce Sales Dashboard

##  Project Overview

This project focuses on building an **E-commerce Sales Dashboard** using **Excel** for initial data cleaning and **Power BI** for interactive visualizations.
The goal is to provide **business insights** into sales performance, customer behavior, and profitability, enabling decision-makers to track KPIs effectively.

---

##  Dataset Information

* **Source**: Publicly available e-commerce sales dataset.
* **Format**: Excel (.xlsx / .csv)
* **Key Columns**:

  * `Order ID` – Unique order number
  * `Order Date` – Date of purchase
  * `Customer Name` – Buyer’s details
  * `Segment` – Type of customer (Consumer, Corporate, Home Office)
  * `Category` – Product category (Technology, Furniture, Office Supplies)
  * `Sub-Category` – Product sub-classification
  * `State/Region` – Location of customer
  * `Sales` – Sales amount
  * `Quantity` – Number of units sold
  * `Discount` – Discount applied
  * `Profit` – Net profit per order

---

##  Tools Used

* **Microsoft Excel**

  * Data cleaning (removing blanks, fixing data types, handling duplicates)
  * Initial exploratory analysis with Pivot Tables & Charts
* **Power BI**

  * Data transformation with **Power Query**
  * Data modeling with **relationships & DAX measures**
  * Interactive dashboard design

---

##  Process Workflow

###  Data Preparation (Excel)

* Imported raw dataset into Excel
* Checked for **null values, duplicate rows, and incorrect data types**
* Created pivot tables to validate **total sales, profit, and discount trends**
* Saved cleaned dataset for Power BI

###  Data Transformation (Power BI – Power Query)

* Loaded Excel dataset into Power BI
* Applied transformations:

  * Changed data types (e.g., Date for Order Date, Currency for Sales/Profit)
  * Extracted **Year, Month, and Week** from Order Date
  * Standardized category and region names
* Built **dimension and fact tables** for a clean star schema

###  Data Modeling (Power BI)

* Established relationships between tables:

  * **Orders → Customers**
  * **Orders → Products**
  * **Orders → Regions**
* Created **DAX Measures**:

  * `Total Sales = SUM(Sales)`
  * `Total Profit = SUM(Profit)`
  * `Profit Margin = DIVIDE(SUM(Profit), SUM(Sales))`
  * `Avg Discount = AVERAGE(Discount)`
  * `Sales YTD = TOTALYTD(SUM(Sales), OrderDate)`

###  Dashboard Development (Power BI)

* Designed interactive reports with:

  * **KPI Cards** (Total Sales, Profit, Profit Margin, Avg Discount)
  * **Bar Charts** (Sales & Profit by Category / Sub-Category)
  * **Map Visualization** (Sales by State/Region)
  * **Line Chart** (Monthly Sales Trend)
  * **Customer Segment Analysis** (Pie/Donut Chart)
  * **Top 10 Products by Sales** (Table/Bar Chart with sorting)
* Added **slicers/filters** for:

  * Year / Month
  * Region / State
  * Category / Segment

---

##  Insights Generated

1. **Sales Trends** – Identified peak sales months and seasonal demand.
2. **Profitability** – Some categories generate sales but very low profit due to high discounts.
3. **Customer Segments** – Consumer segment contributes the most revenue.
4. **Regional Performance** – Certain states perform significantly better (potential focus markets).
5. **Top Products** – Small % of products drive the majority of revenue.

---

##  Future Improvements

* Add **Forecasting (Power BI built-in)** for sales prediction.
* Include **RFM Analysis** (Recency, Frequency, Monetary) for customer segmentation.
* Automate data refresh with scheduled Power BI service.
* Expand dataset to include marketing spend → ROI Analysis.

---

##  Key Learnings

* Hands-on with **Excel pivot analysis + cleaning**.
* Built an **end-to-end BI pipeline** from raw data → clean model → insights.
* Enhanced **DAX & visualization** skills in Power BI.



* **Email**: [gowthamgshivamurthy@gmail.com](mailto:gowthamgshivamurthy@gmail.com)
* **LinkedIn**: [linkedin.com/in/gowthamgshivamurthy](https://www.linkedin.com/in/gowthamgshivamurthy)



