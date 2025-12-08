# 🏏 Virat Kohli: A Data-Driven Century Analysis  
*A Power BI dashboard exploring Virat Kohli’s centuries, leadership impact, and match-winning influence.*

---

## 🖼️ Dashboard Preview  
> Replace with your screenshot  
![Dashboard Preview](Assets/Dashboard_Main.png)

---

# 📌 Overview  
The **Virat Kohli Century Analysis Dashboard** presents an interactive exploration of Virat Kohli’s international centuries across formats, opponents, venues, innings, and captaincy periods.

Built using **Power BI**, this dashboard transforms raw cricket statistics into meaningful insights about one of the greatest modern-day batsmen.

It allows users to:

- Analyse century distribution by opposition  
- Compare performance as captain vs non-captain  
- View match outcomes when Kohli scores 100  
- Explore format-wise influence  
- Study batting patterns and impact on team success  

---

# 🎯 Purpose  
The dashboard aims to answer key analytical questions:

- Which teams does Kohli score the most centuries against?  
- Does captaincy affect his century-scoring ability?  
- How many of his centuries translated into wins?  
- In which formats is he most dominant?  
- How does batting position, venue, or innings impact performance?  

This project is designed to demonstrate **data storytelling**, **visual analytics**, and **sports performance insights** using Power BI.

---

# 🧩 Dataset & Data Model  

## 📁 **1. Player_Info Table**
Contains high-level player metadata:

| Column | Description |
|--------|-------------|
| Full Name | Virat Kohli |
| Born | November 05, 1988 – Delhi |
| Role | Top-order batter |
| Batting Style | Right-hand bat |
| Bowling Style | Occasional bowler |
| Age | Calculated field |

---

## 📁 **2. Virat_Kohli_100s (Fact Table)**  
Each row represents one century:

| Column | Description |
|--------|-------------|
| Number | Century index |
| Format | ODI / Test / T20I |
| Inning | 1st / 2nd |
| Position | Batting position |
| Score | Runs made |
| Balls | Balls faced |
| Opposition | Opponent team |
| Venue | Stadium / Country |
| Result | Win / Loss / Draw / Tie |
| Captain | Yes / No |

---

## ⭐ **Data Model Structure (Star Schema)**  

