# ☕ Coffee Shop Sales & Customer Behavior Analytics Dashboard

An interactive, visually engaging **Microsoft Excel Dashboard** designed to consolidate retail transaction logs, analyze sales trajectories, evaluate weather/demographic impacts, and track customer purchasing behaviors.

---

## 📌 Business Problem & Overview

A retail coffee shop needed a centralized reporting system to monitor daily store performance, purchasing patterns, and sales volume. Management lacked consolidated visibility into how external drivers—such as weather conditions and time of day—as well as customer demographics, loyalty status, and payment preferences affected overall revenue and product popularity.

### Key Business Objectives:
* **Centralize Sales Data:** Aggregate raw transaction logs containing item-level detail, customer demographics, and store operational metadata.
* **Identify Core Revenue Drivers:** Uncover top-selling coffee products, high-volume order times, and peak sales days.
* **Analyze Behavioral Drivers:** Measure the impact of weather conditions, temperature, payment methods, and loyalty tiers on sales and tip amounts.
* **Optimize Operations:** Provide actionable insights to improve store inventory management, staffing levels during peak hours, and targeted promotional strategies.

---

## 🛠️ Tech Stack & Excel Capabilities Used

* **Microsoft Excel**
  * **Power Query & Data Cleaning:** Standardizing raw transactional datasets, formatting timestamps, and organizing categorical fields.
  * **Data Modeling:** Structuring relationship tables and dynamic data flows.
  * **PivotTables & PivotCharts:** Aggregating metrics across multiple dimensions (Time of Day, Weather, Demographics, Loyalty Tiers).
  * **Advanced Excel Formulas:** Utilizing dynamic functions (`GETPIVOTDATA`, `=IFERROR()`, `=SUM()`, `=AVERAGE()`) for key KPI card displays and chart source modeling.
  * **Custom UI & Dashboard Design:** Designed with a thematic brown/coffee visual palette, custom card layouts, dynamic slicers, and structured chart panels.

---

## 📂 File Architecture & Dataset Structure

The workbook (`coffee_shop_sales_dashboard.xlsx`) is structured into three primary worksheets:

| Sheet Name | Purpose & Contents |
| :--- | :--- |
| **`Dashboard`** | The executive user interface featuring high-level KPI cards, interactive slicers (Days, Gender), and visual analytical charts. |
| **`PivotTable`** | The analytical engine holding structured summary tables, average tip metrics, weather matrix calculations, and time series aggregates. |
| **`coffee_shop_sales_dataset`** | The underlying transactional database containing fields such as Transaction ID, Date, Time, Coffee Type, Product, Size, Unit Price, Quantity, Total Sales, Customer ID, Age Group, Gender, Loyalty Status, Payment Method, Tip Amount, Satisfaction Score, Weather, and Employee Count. |

---

## 📊 Key Dashboard Features & Visualizations

### 1. Key Performance Indicators (KPIs)
* **Total Sales:** Displays total accumulated revenue across selected periods (`$843.50`).
* **Total Transactions:** Monitors total order volume (`124` orders).
* **Average Price:** Tracks the average revenue per transaction (`$6.80`).

### 2. Time & Product Analytics
* **Sales by Time of Day:** Donut chart breaking down order volumes across Morning, Afternoon, Evening, and Night time slots.
* **Sales by Product:** Horizontal bar chart highlighting top-performing coffee offerings (e.g., Latte, Mocha, Cappuccino, Flat White, Americano, Espresso).
* **Sales Trend by Month:** Line chart illustrating historical revenue trajectories over time.

### 3. Customer & Demographic Insights
* **Average Tip by Loyal Members:** Bar chart evaluating tipping habits across Bronze, Silver, Gold, and Non-member customer tiers.
* **Customer Age Demographic:** Column chart segmenting transaction frequency across age brackets (`18-25`, `26-35`, `36-50`, `51+`).
* **Payment Method Breakdown:** Donut/Pie distribution showing payment channel preferences (Card, Cash, Digital Wallet, UPI).

### 4. External Environment & Operations
* **Weather Condition Impact:** Comparative horizontal bar chart analyzing sales distribution under various weather patterns (Sunny, Rainy, Cloudy, Snowy, Windy).
* **Interactive Slicers:** Quick-filter side panel enabling real-time drill-down by **Days of the Week** and **Customer Gender**.

---

## 💡 Key Business Insights

1. **Peak Demand Window:** The majority of transactions occur during **Morning** and **Afternoon** peak hours, indicating key operational windows for staffing optimization.
2. **Product Champions:** High-margin espresso-based beverages like **Mocha**, **Latte**, and **Cappuccino** contribute the highest proportion of total sales volume.
3. **Primary Customer Demographic:** The **26–35** and **18–25** age groups constitute the largest customer base, making them prime targets for digital loyalty initiatives.
4. **Weather Influence:** Sales volume remains steady during **Sunny** and **Cloudy** days, while specific beverage categories shift based on weather conditions and temperature variations.

---

## 🚀 How to Open & Explore

1. **Download:** Download `coffee_shop_sales_dashboard.xlsx` from the repository.
2. **Open:** Open using **Microsoft Excel 2016** or newer (Excel 365 recommended).
3. **Enable Content:** Click **Enable Content** on the top yellow message bar if external connections or formulas require permission.
4. **Interact:** Go to the **`Dashboard`** tab and interact with the **Days** or **Gender** slicers to dynamically update all charts and KPI metrics.