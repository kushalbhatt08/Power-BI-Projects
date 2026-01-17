# 🌍 Global Data Jobs Market Dashboard  
*A Power BI dashboard analysing global demand, salary trends, and geographic distribution of data roles.*

---

## 🖼️ Dashboard Preview  
<img width="1533" height="841" alt="Screenshot 2026-01-17 115704" src="https://github.com/user-attachments/assets/b71f918c-5101-4eab-8047-f517375b51e5" />

---

# 📌 Overview  
The **Global Data Jobs Market Dashboard** provides an interactive, data-driven analysis of the worldwide data job landscape.

Built using **Power BI**, this dashboard transforms raw job-market data into meaningful insights, helping users understand **where data jobs are located**, **which roles are most in demand**, and **how salaries vary globally**.

This dashboard is designed for **students, job seekers, and professionals** looking to explore global opportunities in data-related careers.

It allows users to:

- Analyse global demand for different data roles  
- Compare average hourly and yearly salaries  
- Identify the most in-demand data job titles  
- Explore geographic concentration of data jobs  
- Understand global hiring trends in data careers  

---

# 🎯 Purpose  
The dashboard aims to answer key analytical questions:

- Which data roles are most in demand globally?  
- How many data jobs are available worldwide?  
- What are the average salary benchmarks for data professionals?  
- Where are data jobs geographically concentrated?  
- How does demand vary across different data roles?  

This project demonstrates **data storytelling**, **job-market analytics**, and **business-focused dashboard design** using Power BI.

---

# 🧩 Dataset & Data Model  

## 📁 **1. Job_Market_Data (Fact Table)**  
Contains job-level information for data-related roles:

| Column | Description |
|------|-------------|
| Job Title | Data role name |
| Job Count | Number of job postings |
| Country | Job location |
| Average Hourly Salary | Hourly compensation |
| Average Yearly Salary | Annual compensation |
| Region | Geographic region |

---

## 📁 **2. Location / Role Dimensions**
Supporting attributes used for slicing and filtering:

| Attribute | Description |
|----------|-------------|
| Country | Country of job posting |
| Region | Continent / region |
| Role Category | Data Engineer, Analyst, Scientist, etc. |

---

## ⭐ **Data Model Structure (Star Schema)**  
The dashboard follows a **star schema** design for efficient filtering and performance:

- Central **Job Market Fact Table**
- Linked dimension tables for **role**, **location**, and **salary attributes**

---

# 📊 Dashboard Sections  

---

# 📊 1. Market Overview (KPI Section)  
This section provides a high-level snapshot of the global data job market.

### **Metrics Displayed**
| Metric | Value |
|------|------|
| Total Job Count | 478.9K |
| Average Hourly Salary | $49.16 |
| Average Yearly Salary | $120.59K |

**Insight:** The global data job market shows strong demand with competitive salary benchmarks across regions.

---

# 📊 2. Top Data Roles by Demand  
A horizontal bar chart highlighting the most in-demand data roles globally.

### **Top Roles**
- Data Engineer  
- Data Analyst  
- Data Scientist  
- Senior Data Engineer  
- Business Analyst  
- Machine Learning Engineer  

**Insight:** Engineering and analytics-focused roles dominate global hiring trends.

---

# 🌍 3. Geographic Distribution of Data Jobs  
An interactive world map visualising where data jobs are concentrated across countries and regions.

**Insight:**  
- Strong demand in **North America** and **Europe**  
- Growing opportunities in **Asia-Pacific**  
- Emerging markets showing increasing data adoption  

---

# 🔍 Key Insights Summary  
✔ Data Engineer and Analyst roles lead global demand  
✔ Salaries remain highly competitive worldwide  
✔ Data jobs are concentrated in developed economies  
✔ Strong global demand reflects data-driven transformation across industries  
✔ The market offers diverse opportunities across regions and roles  

---

# 🛠️ Tools Used  

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard creation & visualisation |
| **Power Query** | Data cleaning & transformation |
| **DAX** | KPIs, measures, and calculations |
| **CSV Dataset** | Job market data source |

---

## 📄 License  
This project is released under the **MIT License**.  
You are free to use, modify, and distribute this project with proper attribution.

---

# 📬 Contact  
**Kushal Bhatt**  
🔗 GitHub: https://github.com/kushalbhatt08  
🔗 LinkedIn: https://www.linkedin.com/in/kushal-bhatt08/

