# 🏏 Virat Kohli: A Data-Driven Century Analysis  
*A Power BI dashboard exploring Virat Kohli’s centuries, leadership impact, and match-winning influence.*

---

## 🖼️ Dashboard Preview  
<img width="1517" height="841" alt="image" src="https://github.com/user-attachments/assets/8dfd1842-5eee-4b19-8788-08117bbabe6e" />


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

<img width="766" height="421" alt="image" src="https://github.com/user-attachments/assets/a3aa097e-62f2-47b4-93f3-410fdc5d6c9b" />

---

# 📊 Dashboard Sections  

---

# 🏏 1. Player Profile Overview  
This section displays Kohli’s core metrics in one consolidated frame.

<img width="1201" height="367" alt="image" src="https://github.com/user-attachments/assets/ca6c4f67-d826-43a7-8b61-c1d64512a9c9" />


### **Metrics Displayed**
| Metric | Value |
|--------|--------|
| Full Name | Virat Kohli |
| Born | 05 Nov 1988, Delhi |
| Role | Top Order Batter |
| Batting Style | Right-Hand Bat |
| Total Runs | 11,703 |
| Total Innings | 150 |
| Avg. Strike Rate | 103.58 |
| Avg. Team Total | 335.57 |
| MOTM Count | 53 |
| Not Out | 30 |
| Captain | 46 |
| Wins | 65 |

**Insight:** Kohli maintains elite consistency with high strike rates, match-winning knocks, and significant contributions while leading the team.

---

# 📊 2. Opposition, Captaincy & Win Analysis  

<img width="1186" height="358" alt="image" src="https://github.com/user-attachments/assets/20f49eec-f719-4f04-9563-9a2064cc803f" />


---

## 🔹 **Century Count by Opposition (Treemap)**  
Kohli scores the most centuries against:

- **Australia – 17**  
- **Sri Lanka – 15**  
- **West Indies – 12**  
- **South Africa – 9**  
- **New Zealand – 9**  
- **England – 8**

**Insight:** Kohli performs best against top-tier and historically competitive teams.

---

## 🔹 **Centuries as Captain (Donut Chart)**  
- **46 centuries** as Captain (50.55%)  
- **45 centuries** as Non-Captain (49.45%)

**Insight:** Captaincy did *not* reduce his batting performance — he remained equally dominant.

---

## 🔹 **Winning as Captain (Bar Chart)**  
Most of his centuries result in victories:

- **Wins:** 65+  
- **Loss:** ~15  
- **Draw / Tie:** Rare  

**Insight:** Kohli’s centuries are highly correlated with match success.

---

## 🔹 **Format-Wise Wins When Kohli Scores a Century**
| Format | Wins |
|--------|-------|
| ODI | 52 |
| Test | 30 |
| T20 | 8 |
| T20I | 1 |

**Insight:** ODI remains his strongest format, but his Test centuries also contribute heavily to wins.

---

# 🔍 Key Insights Summary  
✔ Performs best vs strong nations (especially Australia & Sri Lanka)  
✔ Captaincy does *not* negatively impact batting output  
✔ Majority of centuries lead directly to team wins  
✔ ODI is his most dominant scoring format  
✔ Shows strong match-winning influence in leadership role  

---

# 🛠️ Tools Used  

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard creation & visuals |
| **Power Query** | Data cleaning & transformation |
| **DAX** | KPIs, calculated measures, filters |
| **Excel / CSV** | Raw data preparation |

---

---

# 📄 License  
This project is released under the **MIT License** (or choose your preferred license).

---

# 📬 Contact  
**Kushal Bhatt**    
🔗 GitHub: https://github.com/kushalbhatt08  
🔗 LinkedIn:[ your LinkedIn link](https://www.linkedin.com/in/kushal-bhatt08/)



