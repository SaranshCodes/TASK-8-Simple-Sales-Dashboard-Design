# 📊 Sales Dashboard – Superstore Dataset

## 📝 Project Overview
This project analyzes sales data from the **Superstore Dataset** to uncover insights into orders, sales, profits, and performance across regions, product categories, and months.  
Data cleaning and preprocessing were done in **Python**, followed by creating an **interactive Power BI dashboard** for visualization.

---

## 🛠 Steps Performed

### 1. Data Cleaning & Preprocessing (Python)
* Loaded the raw dataset using **Pandas**.
* Removed unnecessary columns such as `Row ID`.
* Converted the `Order Date` field into a proper **datetime** datatype.
* Extracted month values from the `Order Date` field for monthly sales analysis.
* Removed rows with missing `Order Date` values.
* Exported the cleaned dataset as a CSV for use in Power BI.

### 2. Data Visualization (Power BI)

Created an interactive dashboard that includes:

* **KPIs**:

  * Total Orders: **2003**
  * Total Sales: **885.46K**
  * Total Profit: **110.35K**
  * Number of States: **47**
* **Visuals**:

  * Sales by Month (Line Chart)
  * Sales and Profit by Region (Combo Chart)
  * Sales by Region (Bar Chart)
  * Sales by Product Category (Donut Chart)
  * Profit by Product Category (Bar Chart)
* **Filters/Slicers**:

  * Segment
  * Ship Mode
  * Region
  * Product Category
  * Year Range Slider

### 🔑 Key Insights

* **West Region** generated the highest sales and profit.
* **Technology** category had the highest profit margin.
* Sales trends show seasonal peaks, especially in **February** and **August**.
* **Furniture** category had the lowest profitability.
