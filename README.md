# 🏆 The Road to Glory — FIFA World Cup 2026 Tournament Intelligence

<p align="center">
  <b>Comprehensive Sports Analytics, Match Dynamics & Team Performance Dashboard in Power BI</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/DAX-Advanced_Calculations-blue?style=for-the-badge" alt="DAX" />
  <img src="https://img.shields.io/badge/Data_Modeling-Star_Schema-success?style=for-the-badge" alt="Star Schema" />
  <img src="https://img.shields.io/badge/Sports_Analytics-FIFA_2026-critical?style=for-the-badge" alt="FIFA 2026" />
</p>

---

## 📌 Executive Overview
**The Road to Glory** is an interactive sports intelligence platform built in Power BI for the expanded 48-team FIFA World Cup 2026 format. Spanning 104 matches, 312 tournament goals, and stadium operations across North America, the dashboard delivers deep match-by-match breakdowns, player discipline, and referee metrics.

### 📊 Core Key Performance Indicators (KPIs)
- ⚽ **Total Tournament Matches:** **104 matches** modeled across group and knockout phases
- 🎯 **Total Goals Analyzed:** **312 goals** with minute-by-minute distribution, set pieces, and player associations
- 🥅 **Average Scoring Intensity:** **3.00 goals / match** baseline across all stages
- 🏟️ **Stadium Capacity & Geographic Footprint:** Modeled across host venues with seating, pitch conditions, and city clusters
- 🟨 **Discipline & Fair Play Metrics:** Comprehensive card allocations, foul frequency, and referee intervention analysis

---

## 🎯 Business Problem & Objectives
1. 📈 **Tournament Progression Tracking:** Separate group-stage and knockout-stage dynamics to evaluate performance across different competition phases.
2. ⏱️ **Event-Level Granularity:** Connect goal timestamps, penalty classifications, disciplinary actions, and referee assignments to determine when match momentum shifts.
3. 🗺️ **Venue & Operational Dynamics:** Analyze stadium capacities, regional clusters, and travel demands across host cities.
4. 🌟 **Individual & Team Benchmarking:** Track top scorers, own-goal frequencies, and disciplinary pressure across participating federations.

---

## 💡 In-Depth Data Analysis & Business Insights
- ⚡ **Scoring Timing & Momentum Windows:** 312 goals across 104 matches yield an average of **3.0 goals per fixture**. Minute distribution reveals concentrated scoring peaks between minutes 60–75 and stoppage time, highlighting tactical fatigue.
- 🔗 **Multi-Layer Performance Analytics:** Match results link with goal events, player discipline, group standings, referees, and stadium dimensions, unlocking multidimensional analysis beyond raw win/loss outcomes.
- ⚖️ **Referee Strictness & Card Allocation:** High-variance card-to-foul ratios among officiating crews demonstrate measurable stylistic differences in foul tolerance and match control.
- 🏟️ **Home Advantage & Cluster Effects:** Stadium elevation, pitch specifications, and geographic clusters impact second-half offensive output and recovery windows.

---

## 🖼️ Dashboard Visual Tour & Storytelling

### 1. Landing Page
<p align="center">
  <img src="./Dashboard%20Previews/Landing%20Page.png" alt="The Road to Glory — Landing" width="95%">
</p>

### 2. Overview Dashboard
<p align="center">
  <img src="./Dashboard%20Previews/Overview.png" alt="The Road to Glory — Overview" width="95%">
</p>

### 3. Stadiums Intelligence
<p align="center">
  <img src="./Dashboard%20Previews/Stadiums.png" alt="The Road to Glory — Stadiums" width="95%">
</p>

### 4. Referees & Officiating
<p align="center">
  <img src="./Dashboard%20Previews/Referees.png" alt="The Road to Glory — Referees" width="95%">
</p>

### 5. Top Scorers & Golden Boot Race
<p align="center">
  <img src="./Dashboard%20Previews/Top%20Scorers.png" alt="The Road to Glory — Top Scorers" width="95%">
</p>

### 6. Own Goals Breakdown
<p align="center">
  <img src="./Dashboard%20Previews/Top%20Own%20Scorers.png" alt="The Road to Glory — Own Goals" width="95%">
</p>

### 7. Player Discipline & Fair Play
<p align="center">
  <img src="./Dashboard%20Previews/Discipline%20Players.png" alt="The Road to Glory — Discipline" width="95%">
</p>

### 8. Match-by-Match Breakdown
<p align="center">
  <img src="./Dashboard%20Previews/Matches.png" alt="The Road to Glory — Matches" width="95%">
</p>

### 9. Group Stage Standings & Dynamics
<p align="center">
  <img src="./Dashboard%20Previews/Group%20Stage.png" alt="The Road to Glory — Group Stage" width="95%">
</p>

### 10. Knockout Stage Bracket & Pathways
<p align="center">
  <img src="./Dashboard%20Previews/Knockout%20Stage.png" alt="The Road to Glory — Knockout Stage" width="95%">
</p>

---

## 🏗️ Data Architecture & Star Schema
The semantic model uses a normalized Star/Snowflake architecture linking event-level fact tables with tournament dimensions:

- **Fact Tables:**
  - `fact_matches` — Match fixtures, dates, stages, stadium keys, and final scores
  - `fact_match_teams` — Team-level performance per match (possession, shots, fouls)
  - `fact_player_goals` — Goal events, timestamps, goal types, and scorer keys
  - `fact_player_discipline` — Yellow/red cards, foul timestamps, and infractions
  - `fact_group_standings` — Points, goal differentials, and tournament rankings
- **Dimension Tables:**
  - `dim_teams`, `dim_players`, `dim_stadiums`, `dim_refereees`, `dim_stage`, `dim_group`

### 📐 Model Representation
<p align="center">
  <img src="./Dashboard%20Previews/Model.png" alt="The Road to Glory — Power BI Data Model" width="95%">
</p>

---

## 🛠️ Tools & Technologies
- 📊 **Power BI Desktop:** Analytical reports, interactive slicers, cross-filtering
- 📐 **DAX (Data Analysis Expressions):** Cumulative points, scoring intensity, card rates
- 🧹 **Power Query (M):** Data ingestion, standardization, event-level fact normalization
- 🎨 **UI/UX Design:** Dark-themed tournament branding with North American host visuals

---

## 📜 License & Author
- **Author:** Kerelos Nakhla ([GitHub](https://github.com/Kerelos-Nakhla))
- **License:** MIT License
