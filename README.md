# 🚗 New Zealand Vehicle Theft Analysis Dashboard

> An end-to-end Excel analytics project analyzing **4,553 vehicle theft incidents** across 13 New Zealand regions — featuring an interactive Power Query dashboard, KPI cards, and actionable insights for law enforcement and insurance stakeholders.

---

## 📌 Project Overview

This project dives deep into vehicle theft patterns across New Zealand using a real-world dataset spanning **October 2021 to April 2022**. Built entirely in Microsoft Excel, it demonstrates the full data analytics pipeline — from raw data cleaning to an interactive, slicer-driven dashboard — without a single line of external code.

Whether you're a data analyst, BI professional, or Excel enthusiast, this project showcases how powerful Excel can be as an analytics tool when used to its full potential.

---

## 📊 Dashboard Preview

### Interactive Dashboard
<img width="1035" height="616" alt="Screenshot 2026-06-17 090628" src="https://github.com/user-attachments/assets/bf36a381-10be-4618-a5fd-973707a5afc6" />


### Key Summary Points
<img width="1010" height="577" alt="Screenshot 2026-06-17 085756" src="https://github.com/user-attachments/assets/75462e02-d4a3-4206-bf64-47d07c8ba518" />


---

## 🔍 Key Findings

| # | Insight | Detail |
|---|---------|--------|
| 🏙️ | **Highest-Theft Region** | Auckland leads with **1,638 thefts** — 36.0% of all NZ vehicle thefts over the 6-month period |
| 📍 | **Highest Theft Rate** | Gisborne at **337.8 thefts per 100,000 residents**, indicating disproportionate per-capita risk |
| 🚙 | **Most Targeted Vehicle Type** | Station wagons (**945 thefts, 20.9%**), followed by saloons and hatchbacks — together over 50% of all thefts |
| 📈 | **Rising Theft Trend** | Incidents rose from **464 (Oct 2021) to 1,053 (Mar 2022)** — a 126.9% surge |
| 💎 | **Luxury vs Standard** | Standard vehicles account for **95.8%** of thefts; luxury vehicles are targeted at a far lower absolute rate |
| 🏷️ | **Most Stolen Make** | **Toyota** with 716 incidents, followed by Nissan and Ford |
| 🌆 | **Population Density Effect** | High-density Auckland leads in volume, but low-density Gisborne (6.2 pop/km²) shows elevated per-capita rates |

---

## 🛠️ Tools & Techniques

| Tool / Feature | Usage |
|----------------|-------|
| **Microsoft Excel** | Core analytics and visualization platform |
| **Power Query** | Data ingestion, transformation, and cleaning |
| **Pivot Tables & Charts** | Aggregations and dynamic visualizations |
| **Slicers & Timelines** | Interactive filtering by region, vehicle type, color, and month |
| **KPI Cards** | Summary metrics with conditional formatting |
| **Conditional Formatting** | Color-coded highlights for anomalies and rankings |

---

## 📁 Dataset

- **Source:** New Zealand Police vehicle theft records
- **Period:** 07 October 2021 – 06 April 2022
- **Total Records:** 4,553 vehicle theft incidents
- **Coverage:** 13 of 16 New Zealand regions

### Key Fields

```
Vehicle_id | Vehicle_type | Make_name | Make_type | Model_year
Color      | Date_stolen  | Region    | Population | Density
```

---

## 📂 Repository Structure

```
📦 NZ-Vehicle-Theft-Analysis
 ┣ 📊 project_beta.xlsx       ← Main Excel workbook (data + dashboard)
 ┣ 📸 dashboard_preview.png   ← Dashboard screenshot
 ┣ 📸 summary_points.png      ← Key summary points screenshot
 ┗ 📄 README.md               ← You are here
```

---

## 💡 Dashboard Features

- **6 KPI Cards** — Total Thefts, Peak Month, Top Region, Top Vehicle Type, Luxury Stolen %, Most Stolen Make
- **Theft Count by Region** — Horizontal bar chart ranked by volume
- **Theft Trend Over Time** — Line chart showing monthly escalation pattern
- **Theft by Vehicle Type** — Pie chart with percentage breakdown
- **Count of Vehicle Type** — Luxury vs Standard comparison chart
- **Top 10 Most-Stolen Vehicle Makes** — Ranked bar chart
- **Interactive Slicers** — Region, Make Type, Month, Vehicle Type, Color filters

---

## 📋 Recommendations

### 🚔 Police Patrol Planning
Prioritize patrols in **Auckland, Canterbury, Bay of Plenty, and Wellington** — which together account for over 70% of all reported thefts. Focus resources on **evening/night hours** based on distribution patterns.

### 🛡️ Insurance Risk Profiling
Insurers should apply **risk-adjusted premiums** for:
1. Station wagons & saloons registered in Auckland and Gisborne
2. **Older model-year vehicles (pre-2005)** which appear heavily in theft records
3. **Silver/white vehicles** — the most commonly stolen colour group

### 📌 Resource Allocation
Patrol resource planning should not focus solely on urban centres. Low-density regions like Gisborne show **disproportionately high per-capita theft rates** that warrant targeted attention.

---

## 🚀 How to Use

1. **Download** `project_beta.xlsx`
2. **Open** in Microsoft Excel (2016 or later recommended)
3. Navigate to the **Dashboard** sheet
4. Use the **slicers** on the left to filter by Region, Vehicle Type, Color, or Month
5. Explore the **Summary Points** sheet for written analytical insights

---

## 👤 Author

**[G Dhananjay Chauhan]**
Data Analyst | Excel & Power BI Enthusiast
---

## ⭐ If you found this useful...

Give the repo a **star** ⭐ — it helps others discover the project and motivates more open analytics work like this!

---

*Data covers the period 07 October 2021 to 06 April 2022. All figures are derived from the uploaded dataset and reflect only the 13 regions present in the data.*
