# Executive Financial Performance Dashboard

## 📊 Project Overview
This project is an interactive, enterprise-grade financial monitoring dashboard built in Power BI. It is designed to provide a single-view financial performance summary for management and stakeholders, transforming raw daily transaction data into actionable, high-level business intelligence.

## 📸 Dashboard Preview

> **Note:** Watch the full interactive video demo here:
> **[PASTE YOUR VIDEO DEMO LINK HERE]**

![Final Dashboard Layout](PASTE YOUR DASHBOARD SCREENSHOT LINK HERE)

## 🎯 Business Value & Objectives
The primary goal of this dashboard is to make complex financial insights accessible to management anywhere, instantly. 

By utilizing advanced DAX modeling and AI-driven analytics, this tool allows executives to:
* Monitor bottom-line KPIs at a glance.
* Track historical profit and revenue trends.
* Compare Actual vs. Budgeted revenue across multiple departments.
* Perform drill-down analysis into specific regions and product categories.

## 🛠️ Key Dashboard Components
* **KPI Cards:** Top-level summary of Total Revenue, Total Expenses, Net Profit, and Profit Margin %.
* **Predictive Line Chart:** Revenue and Profit trends featuring an AI-generated 6-month forecast.
* **Anomaly Detection Chart:** Daily revenue tracking utilizing Power BI's built-in AI anomaly detection (set to 80% sensitivity) to automatically flag irregular financial spikes and dips.
* **Clustered Bar Chart:** A direct Budget vs. Actual comparison broken down by Department.
* **Map Visual:** Geographic visualization of Profit distribution by Region.
* **Donut Chart:** Profit contribution broken down by specific Product Categories.
* **Interactive Slicers:** Dropdown controls allowing users to filter the entire dashboard by Time (Year/Quarter/Month), Region, and Product.

## 💻 Technical Implementation
* **Data Modeling:** Built utilizing a Star Schema structure, connecting raw financial data to a centralized Date Table.
* **DAX Calculations:** Custom measures created for tracking profit margins, budgeting, and aggregating total revenue.
* **AI Analytics:** Overcame native Power BI continuous/categorical axis limitations by deploying a side-by-side visual strategy to satisfy both Forecasting and Anomaly data requirements.

## 📂 How to Use This Repository
1. Download the `Financial_Dashboard.pbix` file.
2. Open the file in **Power BI Desktop**.
3. Use the Slicers in the top right corner to interact with the data and see the metrics recalculate in real-time.
4. For a quick static review, download the included `Dashboard_Report.pdf`.
