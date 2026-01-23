# 💰 Financial Analysis Report Dashboard

*A Power BI dashboard analysing sales performance, cost efficiency, profitability, and business drivers across products, segments, and countries.*

---

## 🖼️ Dashboard Preview

<img src="Report.png" alt="Financial Analysis Dashboard" width="100%" />


---

## 📌 Overview

The **Financial Analysis Report Dashboard** provides a comprehensive, business-focused analysis of **Sales**, **Cost of Goods Sold (COGS)**, and **Profitability** across multiple dimensions.

Built using **Power BI**, this dashboard converts transactional financial data into **actionable business insights**, enabling stakeholders to monitor performance trends, identify profit drivers, and support strategic decision-making.

This dashboard is designed for **business analysts, finance teams, and decision-makers** who require a clear, interactive view of financial performance.

It allows users to:

- Track sales, cost, and profit trends over time  
- Identify top-performing products  
- Analyse revenue contribution by customer segment  
- Evaluate the impact of discount levels on sales share  
- Compare Sales vs COGS across countries  
- Monitor monthly and regional performance patterns  

---

## 📌 Business Problem Statement

In real-world business environments, **building a dashboard alone is not sufficient**. The real challenge lies in deeply understanding the **business context**, **data limitations**, and **decision-making needs** of stakeholders before designing an analytical solution.

The key challenges addressed in this project included:

- Limited visibility into overall **Sales**, **COGS**, and **Profit** trends  
- Lack of clarity around **top-performing products** and revenue-driving segments  
- Difficulty assessing how **different discount levels impact sales share**  
- Inability to effectively compare **Sales vs COGS across countries**  
- Dependence on **static and fragmented reports**, slowing data-driven decisions  

Additionally, the dataset was **not perfectly clean**, reflecting real business scenarios where data transformation, assumptions, and modelling must align with business expectations rather than ideal conditions.

This dashboard was designed to **bridge the gap between raw financial data and executive-level insights**, enabling faster and more confident decision-making.

---

## 🎯 Purpose

The dashboard aims to answer key financial and business questions:

- How are **Sales**, **Cost**, and **Profit** trending over time?  
- Which products contribute the most to total sales?  
- Which customer segments generate the highest revenue?  
- How do discount levels influence sales distribution?  
- Which countries have higher costs relative to sales?  
- Where are the strongest and weakest profit areas?  

This project demonstrates **financial analytics**, **business intelligence**, and **data storytelling** using Power BI.

---

## 🧩 Dataset & Data Model

### 📁 1. Financial Data (Fact Table)

Contains transactional financial records:

| Column | Description |
|------|------------|
| Date | Transaction date |
| Product | Product name |
| Country | Sales country |
| Segment | Customer segment |
| Sales | Total sales value |
| COGS | Cost of goods sold |
| Profit | Sales minus COGS |
| Discount Band | Discount category |

---

### 📁 2. Supporting Dimensions

| Dimension | Description |
|---------|------------|
| Product | Product hierarchy |
| Country | Geographic classification |
| Segment | Customer type |
| Discount Band | Discount level grouping |
| Date | Time intelligence |

---

### ⭐ Data Model Structure (Star Schema)

The dashboard follows a **star schema** design to ensure optimal performance and accurate filtering:

- Central **Financial Fact Table**  
- Connected dimension tables for **Product**, **Country**, **Segment**, **Discount**, and **Date**

---

## 📊 Dashboard Sections

### 📊 1. Financial Overview (KPI Section)

This section provides a high-level snapshot of overall business performance.

**Key Metrics Displayed**

| Metric | Value |
|------|------|
| Total Sales | 49.11M |
| Total Profit | 8.63M |
| COGS Count | 292 |
| Top Product | Paseo |

**Insight:**  
The business generates strong sales volume, with profitability concentrated in a few key products.

---

### 📊 2. Sales, Cost & Profit Trends Over Time

A combined bar and line chart illustrating **Sales**, **COGS**, and **Profit** trends by date.

**Insight:**  
Sales and profitability fluctuate across the week, highlighting peak-performing periods and potential cost inefficiencies.

---

### 📊 3. Discount vs Sales Share

A donut chart showing how sales are distributed across different discount levels.

**Insight:**  
Low-discount transactions contribute the largest share of sales, indicating healthier margins compared to high-discount strategies.

---

### 📊 4. Segment Revenue Split

A pie chart breaking down revenue by customer segment.

**Insight:**  
Government and Small Business segments dominate total revenue, while Enterprise and Midmarket segments present growth opportunities.

---

### 📊 5. Monthly Sales Performance

A horizontal bar chart comparing sales across months.

**Insight:**  
October and December show peak sales performance, indicating seasonal demand patterns.

---

### 📊 6. Product Sales Performance

A funnel-style visual ranking products by total sales contribution.

**Insight:**  
**Paseo** is the top-performing product, followed by **VTT** and **Montana**, accounting for a significant portion of total revenue.

---

### 📊 7. Sales vs COGS by Country

A line and area chart comparing **Sales** and **COGS** across countries.

**Insight:**  
Some countries show narrower gaps between Sales and COGS, highlighting regions where cost optimisation could improve profitability.

---

## 🔍 Key Insights Summary

✔ Sales performance is driven by a small number of top products  
✔ Low-discount sales generate the strongest revenue share  
✔ Profitability varies significantly across countries  
✔ Government and Small Business segments dominate revenue  
✔ Seasonal trends impact monthly performance  
✔ The dashboard enables faster, data-driven financial decisions  

---

## 🛠️ Tools Used

| Tool | Purpose |
|-----|--------|
| **Power BI Desktop** | Dashboard development |
| **Power Query** | Data cleaning & transformation |
| **DAX** | KPI calculations & measures |
| **Excel / CSV** | Financial data source |

---

## 📄 License

This project is released under the **MIT License**.  
You are free to use, modify, and distribute this project with proper attribution.

---

## 📬 Contact

**Kushal Bhatt**  
🔗 GitHub: https://github.com/kushalbhatt08  
🔗 LinkedIn: https://www.linkedin.com/in/kushal-bhatt08/

