# 🏏 IPL Analysis Dashboard (2008–2025)

![IPL Dashboard](ipl.gif)

An end-to-end **Power BI analytics project** that explores Indian Premier League (IPL) data from **2008 to 2025**. This dashboard provides season-wise insights into team performance, player achievements, match outcomes, and tournament highlights using **advanced DAX**, data modeling, and rich visuals.

---

## 📌 Project Overview

The goal of this project is to build an **interactive and insight-driven IPL dashboard** that answers key cricketing and analytical questions such as:

* Who won a particular IPL season?
* Which player secured the **Orange Cap** and **Purple Cap**?
* How did teams perform across wins, losses, ties, and no-results?
* Who dominated boundaries (4s & 6s) in a season?
* What were the overall tournament statistics for a selected season?

The dashboard is fully **dynamic** and responds to season selection via slicers.

---

## 📊 Key Features

### 🔹 Tournament Summary

* Season Winner & Runner-up (with team logos)
* Total Matches played
* Total Teams participated
* Total Venues

### 🔹 Batting Insights

* Total 4’s & 6’s in a season
* Total Centuries & Half-Centuries
* **Orange Cap**:

  * Player Name
  * Total Runs
  * Team Name
  * Player Image
* Top Fours & Sixes:

  * Player Name
  * Count
  * Team
  * Player Image

### 🔹 Bowling Insights

* **Purple Cap**:

  * Player Name
  * Total Wickets
  * Team Name
  * Player Image

### 🔹 Points Table

* Matches Played
* Wins, Losses, Ties, No Results
* Total Points
* Team Logos for better readability

---

## 🧠 DAX & Data Modeling Highlights

This project makes extensive use of **advanced DAX patterns**, including:

* `VAR / RETURN` for readable and optimized measures
* `SELECTEDVALUE()` for slicer-driven season analysis
* `CALCULATE()` with complex filter context
* `FILTER()` and `SUMMARIZE()` for player-level aggregations
* `USERELATIONSHIP()` to activate inactive relationships (team1 / team2 logic)
* `MAXX()` and `COUNTROWS()` for ranking and award logic
* `CALCULATETABLE()` for top-performer extraction
* `LOOKUPVALUE()` for dynamic image rendering
* `KEEPFILTERS()` for controlled context propagation

---

## 🗂️ Data Sources

* **Match-level data** (season, teams, venue, result, winner)
* **Ball-by-ball data** (runs, wickets, batters, bowlers)
* **Teams reference data** (team names, logos)
* **Players reference data** (player names, images)

All datasets were cleaned and modeled before visualization.

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Power Query** for data cleaning & transformation
* **DAX Studio** (for model inspection and optimization)

---

## 📈 Dashboard Preview

> The dashboard includes:

* Season slicer (top-right)
* KPI cards for quick insights
* Player award cards with images
* Interactive points table

*(Add screenshots here if uploading to GitHub)*

---

## 🚀 How to Use

1. Open the `.pbix` file in **Power BI Desktop**
2. Use the **Season slicer** to switch between IPL seasons
3. Interact with visuals to explore team and player performance

---

## 🧩 Learning Outcomes

Through this project, I strengthened my skills in:

* Analytical dashboard design
* Writing optimized and reusable DAX measures
* Handling complex filter contexts
* Sports analytics & storytelling
* Building recruiter-ready Power BI projects

---

## 👤 Author

**Supratim Mukherjee**
Designed and Developed by Supratim Mukherjee
