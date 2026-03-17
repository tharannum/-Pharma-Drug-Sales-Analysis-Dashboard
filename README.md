# 💊 Pharma Drug Sales Analysis Dashboard (Power BI)

## **Executive Summary**

The pharmaceutical industry generates large volumes of sales data across multiple time intervals, drug categories, and therapeutic classes. However, raw data alone cannot provide meaningful insights without structured analysis and visualization.

This Business Intelligence project analyzes pharmaceutical drug sales data using Power BI to uncover insights into sales trends, category performance, and demand patterns across time.

The dashboard transforms multi-source pharmaceutical sales data into an interactive analytical report that helps stakeholders understand:

* Drug category performance based on ATC classification
* Sales trends across daily, weekly, monthly, and hourly levels
* High-demand drugs and peak sales periods
* Sales stability and contribution of key drugs
* Comparative performance against average benchmarks

The goal is to deliver clear, data-driven insights that support decision-making in inventory management, demand forecasting, and operational planning.

![Pharma Drug Sale Analysis](https://github.com/tharannum/-Pharma-Drug-Sales-Analysis-Dashboard/blob/main/Pharma%20Drug%20Sale%20Analysis.png)

---

## 📊 Pharma Sales Performance Dashboard

The **Pharma Drug Sales Dashboard** provides a comprehensive view of drug sales performance across multiple time dimensions and categories.

It acts as a centralized analytical platform where stakeholders can monitor trends, identify high-performing drugs, and optimize business strategies.

### **Key KPIs Displayed**

* Total Drugs Analyzed: **57**
* Drug Categories (ATC): **8**
* Time Period Covered: **2014 – 2019**
* Sales Granularity: **Hourly, Daily, Weekly, Monthly**

These KPIs help measure the scale, diversity, and temporal distribution of pharmaceutical sales.

---

## 🗂️ 1. Project Overview

The purpose of this project is to convert raw pharmaceutical sales data into an interactive Power BI dashboard that provides actionable insights.

The dashboard helps answer questions such as:

* Which drug categories generate the highest sales?
* How do sales vary across time (hourly to yearly)?
* Which drugs contribute most to total revenue?
* When does peak demand occur during the day?
* How stable are monthly sales compared to averages?

Using Power BI, the dataset was transformed into a clean, structured, and interactive report for effective analysis.

---

## 🗃️ 2. Data Description

### **Datasets**

The project integrates four datasets stored as CSV files:

* Daily Sales Data
* Weekly Sales Data
* Monthly Sales Data
* Hourly Sales Data

---

### **Data Preparation (Power Query)**

Data cleaning and transformation were performed using Power Query:

* Fixed inconsistent date formats (split & merge operations)
* Removed duplicate and null records
* Cleaned and standardized columns
* Handled data errors
* Structured time-based fields for analysis

---

### **Data Model**

A relational data model was designed to enable accurate analysis across different time intervals.

#### **Fact Tables**

* Sales (Daily, Weekly, Monthly, Hourly)

#### **Dimensions**

* Drug Category (ATC Classification)
* Time (Date, Week, Month, Year)

#### **Relationships**

* Many-to-One relationships between sales tables and drug categories
* Linked using drug classification codes (e.g., M01AB, N02BE)

This structure ensures consistent filtering and cross-analysis across all visuals.

---

## 📈 3. Analysis Performed

### **Power Query Transformations**

* Data cleaning and normalization
* Date format standardization
* Removal of inconsistencies and duplicates
* Structuring hierarchical time data

---

### **DAX Measures (KPIs)**

Key performance metrics were created using DAX:

* Total Monthly Sales
* Average Monthly Sales
* Weekly Sales Contribution (N02BE)
* Highest Hourly Sales Count
* Total Sales by Category

---

### **Visualizations**

The dashboard includes a variety of interactive visuals:

#### **KPI Cards**

* Total Monthly Sales
* Average Sales
* Peak Hourly Sales

#### **Sales Trend Analysis**

* Monthly and yearly sales trends (Area & Line Charts)
* Quarterly comparisons

#### **Category Performance**

* Weekly sales by category (Stacked Column Chart)

#### **Contribution Analysis**

* Daily sales contribution (Pie Chart)

#### **Hourly Demand Analysis**

* Sales quantity by hour (Stacked Bar Chart)

#### **Comparative Analysis**

* Total vs Average sales comparison

These visuals allow users to explore trends dynamically and identify patterns across different dimensions.

---

## ❓ 4. Business Questions Answered

The dashboard helps answer key analytical questions such as:

* Which drug contributes the most to total sales?
* How does sales performance vary across time intervals?
* What are the peak hours for drug demand?
* Which months underperform compared to the average?
* How stable are sales trends over time?
* What is the contribution of key drugs like N02BE?

---

## 🔍 5. Key Insights

### **Insight 1 — Dominance of N02BE Drug**

The N02BE drug category contributes approximately **50% of total daily sales**, making it a key revenue driver.

---

### **Insight 2 — Peak Hour Demand Patterns**

Hourly analysis reveals specific time windows where drug sales peak, enabling better inventory and staffing decisions.

---

### **Insight 3 — Seasonal and Monthly Variations**

Certain months (e.g., March) show noticeable fluctuations in sales, indicating possible seasonal demand trends.

---

### **Insight 4 — Sales Stability Analysis**

Comparison between total and average monthly sales highlights periods of underperformance, helping identify inconsistencies.

---

### **Insight 5 — Category-Level Performance**

Different ATC categories show varied contribution levels, indicating opportunities for optimization and focus.

---

## 📌 6. Recommendations

### **Inventory Optimization**

Stock high-demand drugs like N02BE more efficiently to prevent shortages.

### **Demand Forecasting**

Use hourly and weekly trends to improve forecasting accuracy.

### **Operational Planning**

Align staffing and logistics with peak sales hours.

### **Category Strategy**

Focus on underperforming drug categories for growth opportunities.

### **Sales Monitoring**

Continuously compare actual sales with averages to detect anomalies early.

---

## 🛠️ 7. Skills Used

* Power BI Desktop
* Power Query (Data Transformation)
* DAX (Measures & KPIs)
* Data Cleaning & Preprocessing
* Data Modeling (Relationships)
* Business Intelligence Reporting
* Data Visualization
* Analytical Thinking

---

## 🏁 8. Project Outcome

This project delivers:

* A professional and interactive Power BI dashboard
* A clean and structured pharmaceutical dataset
* Multi-level time-based sales analysis
* Insights into drug performance and demand patterns
* A data-driven approach to decision-making

The dashboard enables stakeholders to understand sales behavior, optimize inventory, and make informed strategic decisions in the pharmaceutical domain.

 
