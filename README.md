# 🏏 IPL Data Analysis Dashboard (Power BI)

## 📌 Project Overview
This project analyzes Indian Premier League (IPL) match and ball-by-ball data to uncover
key insights related to season trends, team performance, toss decisions, and player performance.
The dashboard is built using **Power BI Desktop** with interactive visuals and slicers.

---

## 🎯 Objectives
- Analyze season-wise IPL match trends
- Identify most successful teams
- Study toss decision patterns
- Find top-performing batsmen and bowlers
- Build an interactive and user-friendly Power BI dashboard

---

## 🧰 Tools & Technologies Used
- **Power BI Desktop**
- **Excel**
- **SQL (for data understanding & logic building)**
- IPL Dataset (Kaggle)

---

## 📂 Dataset Details
- **matches.csv** – Match-level information (season, teams, toss, winner, venue)
- **deliveries.csv** – Ball-by-ball data (runs, wickets, batsmen, bowlers)

Relationship used:
matches.id → deliveries.match_id

---

## 📊 Dashboard Pages

### 1️⃣ Overview Dashboard
Key insights:
- Season-wise IPL matches
- Team-wise total wins
- Toss decision distribution (Bat vs Field)
- Total IPL matches (KPI Card)

### 2️⃣ Player Performance Dashboard
Key insights:
- Top 10 batsmen by total runs
- Top 10 bowlers by total wickets
- Season-wise filter for interactive analysis

---

## 🖼 Dashboard Preview

### Overview Dashboard
![Overview Dashboard](Screenshots/overview_dashboard.png)

### Player Performance Dashboard
![Player Performance Dashboard](Screenshots/player_performance.png)

> Note: Due to Power BI Service access limitations, the interactive dashboard
> is demonstrated using screenshots.

---

##  Project Structure
IPL-Data-Analysis/
│
├── Dataset/
│ ├── matches.csv
│ └── deliveries.csv
│
├── PowerBI/
│ └── IPL_Analysis.pbix
│
├── Screenshots/
│ ├── overview_dashboard.png
│ └── player_performance.png
│
└── README.md



---

##  Key Insights
- Teams prefer to **field first** after winning the toss
- **Mumbai Indians and CSK** are among the most successful teams
- **Top batsmen and bowlers** change dynamically based on season selection
- Season-wise trends show variation in match volume over the years


##  Author
**Talim Khan**  
Data Analyst | SQL | Excel | Power BI  

---

##  Notes
- Dashboard can be published to Power BI Service using a work/school account
