# The Road to Glory — FIFA World Cup 2026 Tournament Intelligence

<p align="center">
  <b>Comprehensive Sports Analytics, Match Dynamics & Team Performance Dashboard in Power BI</b>
</p>

---

## Executive Overview
**The Road to Glory** is an interactive, analytical tournament intelligence dashboard built in Power BI for the expanded 48-team FIFA World Cup 2026 format. Spanning 104 matches, 312 tournament goals, and stadium operations across North America, the dashboard delivers deep match-by-match breakdowns, player discipline, and referee metrics.

### Tournament Analytics (Calculated from Production Data)
- **Total Tournament Matches:** 104 matches modeled across group and knockout phases
- **Total Goals Analyzed:** 312 goals with minute distribution, set pieces, and player associations
- **Stadium Capacity & Geographic Footprint:** Modeled across host venues with seating, pitch conditions, and city clusters
- **Discipline & Fair Play Metrics:** Comprehensive card allocations, foul frequency, and referee intervention analysis

---


## Business Questions & Key Analytical Takeaways
- **Scoring intensity:** 312 goals across 104 matches produces an average of **3.0 goals per match**, providing a baseline for comparing scoring patterns across stages, teams, and match contexts.
- **Multi-layer performance analysis:** Match results are linked with goal events, player discipline, group standings, referees, and stadium dimensions, enabling analysis beyond simple win/loss reporting.
- **Tournament progression:** Separating group-stage and knockout-stage facts allows performance to be evaluated by competition phase rather than treating the tournament as one homogeneous population.
- **Event-level granularity:** Goal minutes, penalty classifications, disciplinary actions, and referee assignments make the dataset suitable for analyzing when and how match events influence outcomes.

## Dashboard Visual Tour & Storytelling

### 1. Landing
<p align="center">
  <img src="./Dashboard%20Previews/Landing%20Page.png" alt="The Road to Glory — Landing" width="95%">
</p>

### 2. Overview
<p align="center">
  <img src="./Dashboard%20Previews/Overview.png" alt="The Road to Glory — Overview" width="95%">
</p>

### 3. Stadiums
<p align="center">
  <img src="./Dashboard%20Previews/Stadiums.png" alt="The Road to Glory — Stadiums" width="95%">
</p>

### 4. Referees
<p align="center">
  <img src="./Dashboard%20Previews/Referees.png" alt="The Road to Glory — Referees" width="95%">
</p>

### 5. Top Scorers
<p align="center">
  <img src="./Dashboard%20Previews/Top%20Scorers.png" alt="The Road to Glory — Top Scorers" width="95%">
</p>

### 6. Own Goals
<p align="center">
  <img src="./Dashboard%20Previews/Top%20Own%20Scorers.png" alt="The Road to Glory — Own Goals" width="95%">
</p>

### 7. Discipline
<p align="center">
  <img src="./Dashboard%20Previews/Discipline%20Players.png" alt="The Road to Glory — Discipline" width="95%">
</p>

### 8. Matches
<p align="center">
  <img src="./Dashboard%20Previews/Matches.png" alt="The Road to Glory — Matches" width="95%">
</p>

### 9. Group Stage
<p align="center">
  <img src="./Dashboard%20Previews/Group%20Stage.png" alt="The Road to Glory — Group Stage" width="95%">
</p>

### 10. Knockout Stage
<p align="center">
  <img src="./Dashboard%20Previews/Knockout%20Stage.png" alt="The Road to Glory — Knockout Stage" width="95%">
</p>

---

## Data Architecture & Model
The analytical model utilizes a dimensional architecture connecting tournament fixtures, performance events, and master athlete dimensions.

### Model Representation
<p align="center">
  <img src="./Dashboard%20Previews/Model.png" alt="The Road to Glory — Power BI Data Model" width="95%">
</p>

- **Fact Tables:**
  - `fact_matches`: 104 fixtures, stage identifiers, scores, attendance, and referee assignments.
  - `fact_player_goals`: 312 goal records, minute timestamps, penalty classifications, and game-winning weights.
  - `fact_player_discipline`: Disciplinary actions, caution frequency, and suspension triggers.
  - `fact_group_standings`: Points, goal differences, and head-to-head tiebreakers.
- **Dimensions:**
  - `dim_teams`, `dim_players`, `dim_stadiums`, `dim_referees`, `dim_stage`, and `dim_group`.

---

## Tools & Technologies
- **Business Intelligence:** Microsoft Power BI Desktop
- **Data Modeling:** Dimensional Star Schema with relationship integrity
- **DAX Calculations:** Dynamic Standings, Head-to-Head Point Differentials, Fair Play Scoring Indices
- **UI Design:** Custom stadium and tournament aesthetic with high-contrast data visualization

---

## License & Usage
This repository is released under the [MIT License](LICENSE). Developed by **Kerelos Nakhla** — Data Analyst & BI Developer.
