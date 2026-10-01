# 🏆 The Road to Glory — FIFA World Cup 2026 Tournament Intelligence

<p align="center">
  <b>Comprehensive Sports Analytics, Match Dynamics, Player Performance & Stadium Intelligence in Power BI</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/DAX-Sports_Analytics-blue?style=for-the-badge" alt="DAX" />
  <img src="https://img.shields.io/badge/FIFA-World_Cup_2026-critical?style=for-the-badge" alt="FIFA 2026" />
  <img src="https://img.shields.io/badge/Data_Model-Star_Schema-success?style=for-the-badge" alt="Star Schema" />
  <img src="https://img.shields.io/badge/Tournament-104_Matches-orange?style=for-the-badge" alt="104 Matches" />
</p>

---

## 📌 Executive Overview

**The Road to Glory** is an enterprise-grade sports intelligence platform engineered in **Power BI** for the historic **48-nation FIFA World Cup 2026**, co-hosted across the United States, Mexico, and Canada. Covering the complete tournament lifecycle across **104 matches**, **16 host stadiums**, **48 national teams**, and **205 registered star players**, the platform delivers deep analytical visibility into match dynamics, goal-scoring efficiency, discipline telemetry, officiating loads, and venue capacity utilization.

Through unified multi-fact star schema modeling and advanced DAX measures, this solution turns raw match events and standings into interactive tactical scorecards, tournament tree bracket trackers, and executive performance heatmaps.

```
+----------------------------------------------------------------------------------------------------+
|                                    TOURNAMENT AT A GLANCE (FIFA 2026)                              |
+--------------------------+--------------------------+-----------------------+----------------------+
|       104 Matches        |      308 Total Goals     |   2.96 Goals / Match  | 5,850,744 Attendance |
|   48 National Teams      |    16 Host Stadiums      |  25 Elite Referees    | 80,824 Peak Stadium  |
+--------------------------+--------------------------+-----------------------+----------------------+
```

---

## 📊 Tournament Scorecard & Core Performance KPIs

The tournament scorecard summarizes operational and athletic benchmarks across all 104 matches:

| Metric | Total Tournament | Group Stage (72 Matches) | Knockout Stage (32 Matches) | Benchmark / Record Note |
| :--- | :---: | :---: | :---: | :--- |
| **Total Matches Played** | **104** | 72 Matches (69.2%) | 32 Matches (30.8%) | Expanded 48-team tournament format |
| **Total Goals Scored** | **308** | 215 Goals (69.8%) | 93 Goals (30.2%) | **2.96 Goals per Match** tournament avg |
| **Normal Play Goals** | **298** | 208 Goals | 90 Goals | Open play, set pieces & penalties |
| **Own Goals Conceded** | **14** | 7 Goals | 7 Goals | 4.49% of all tournament goals |
| **Total Stadium Attendance** | **5,850,744** | 3,684,327 | 2,166,417 | **56,257 Average Attendance / Match** |
| **Peak Single-Match Attendance**| **80,824** | Estadio Azteca (MEX) | MetLife Stadium (USA) | 80,663 at the World Cup Final |
| **Participating Teams** | **48 Teams** | 12 Groups (4 teams each) | 32 Qualified Teams | Round of 32 expansion |
| **Host Countries & Venues** | **3 Nations / 16 Venues**| USA (11), MEX (3), CAN (2)| Final at MetLife Stadium | 1,033,829 total seat capacity |
| **Active Referees** | **25 Match Officials** | 21 Represented Nations | Final: Szymon Marciniak | 4.16 average appointments / referee |

---

## 🏟️ Host Stadium Infrastructure & Capacity Utilization

The 2026 tournament leverages 16 state-of-the-art venues across North America:

| Stadium Name | Host City | Host Country | Capacity | Total Matches | Total Attendance | Avg Attendance | Capacity Utilization |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Estadio Azteca** | Mexico City | Mexico 🇲🇽 | **80,824** | 5 | 404,120 | 80,824 | **100.0%** |
| **MetLife Stadium** | New York/New Jersey | United States 🇺🇸 | **80,663** | 8 | 645,304 | 80,663 | **100.0%** |
| **AT&T Stadium** | Dallas | United States 🇺🇸 | **70,649** | 9 | 635,841 | 70,649 | **100.0%** |
| **SoFi Stadium** | Los Angeles | United States 🇺🇸 | **70,492** | 8 | 563,936 | 70,492 | **100.0%** |
| **Arrowhead Stadium** | Kansas City | United States 🇺🇸 | **69,045** | 6 | 414,270 | 69,045 | **100.0%** |
| **Levi's Stadium** | San Francisco Bay Area | United States 🇺🇸 | **68,827** | 6 | 412,962 | 68,827 | **100.0%** |
| **NRG Stadium** | Houston | United States 🇺🇸 | **68,777** | 7 | 481,439 | 68,777 | **100.0%** |
| **Lincoln Financial Field** | Philadelphia | United States 🇺🇸 | **68,324** | 6 | 409,944 | 68,324 | **100.0%** |
| **Mercedes-Benz Stadium** | Atlanta | United States 🇺🇸 | **68,239** | 8 | 545,912 | 68,239 | **100.0%** |
| **Lumen Field** | Seattle | United States 🇺🇸 | **66,925** | 6 | 401,550 | 66,925 | **100.0%** |
| **Hard Rock Stadium** | Miami | United States 🇺🇸 | **64,478** | 7 | 451,346 | 64,478 | **100.0%** |
| **Gillette Stadium** | Boston | United States 🇺🇸 | **64,146** | 7 | 449,022 | 64,146 | **100.0%** |
| **BC Place** | Vancouver | Canada 🇨🇦 | **52,497** | 7 | 367,479 | 52,497 | **100.0%** |
| **Estadio BBVA** | Monterrey | Mexico 🇲🇽 | **51,243** | 4 | 204,972 | 51,243 | **100.0%** |
| **Estadio Akron** | Guadalajara | Mexico 🇲🇽 | **45,664** | 4 | 182,656 | 45,664 | **100.0%** |
| **BMO Field** | Toronto | Canada 🇨🇦 | **43,036** | 6 | 258,216 | 43,036 | **100.0%** |
| **Total / Overall** | **16 Host Cities** | **3 Countries** | **1,033,829** | **104** | **5,850,744** | **56,257** | **100.0%** |

---

## ⚽ Golden Boot Race & Top Goal Scorers

The tournament featured prolific offensive output across all stages, highlighted by the Golden Boot race:

| Rank | Player Name | National Team | Position | Normal Goals | Own Goals | Total Goals | Goals / Match Ratio |
| :---: | :--- | :--- | :---: | :---: | :---: | :---: | :---: |
| 🥇 **1** | **Kylian Mbappé** | France 🇫🇷 | Forward | **10** | 0 | **10** | **1.43** |
| 🥈 **2** | **Lionel Messi** | Argentina 🇦🇷 | Forward / Playmaker | **8** | 0 | **8** | **1.14** |
| 🥉 **3** | **Erling Haaland** | Norway 🇳🇴 | Striker | **7** | 0 | **7** | **1.40** |
| 4 | **Jude Bellingham** | England 🏴󠁧󠁢󠁥󠁮󠁧󠁿 | Midfielder | **7** | 0 | **7** | **1.00** |
| 5 | **Harry Kane** | England 🏴󠁧󠁢󠁥󠁮󠁧󠁿 | Striker | **6** | 0 | **6** | **0.86** |
| 6 | **Folarin Balogun** | United States 🇺🇸 | Forward | **6** | 0 | **6** | **1.20** |
| 7 | **Ousmane Dembélé** | France 🇫🇷 | Winger | **6** | 0 | **6** | **0.86** |
| 8 | **Mikel Oyarzabal** | Spain 🇪🇸 | Forward | **5** | 0 | **5** | **0.83** |
| 9 | **Julián Quiñones** | Mexico 🇲🇽 | Forward | **4** | 0 | **4** | **0.80** |
| 10 | **Vinícius Júnior** | Brazil 🇧🇷 | Winger | **4** | 0 | **4** | **0.80** |

---

## 🥅 Tournament Stage Dynamics & Goal Distribution

Tournament scoring and attendance progression from opening fixtures to the Final:

| Tournament Stage | Matches | Total Attendance | Avg Attendance | Total Goals | Goals / Match | High-Scoring Match Example |
| :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| **Group Stage** | 72 | 3,684,327 | 51,171 | **215** | 2.99 | Group stage qualification clashes |
| **Round of 32** | 16 | 1,058,137 | 66,134 | **42** | 2.63 | Inaugural 32-team knockout round |
| **Round of 16** | 8 | 556,898 | 69,612 | **23** | 2.88 | High-intensity continental rivalries |
| **Quarter Finals** | 4 | 267,826 | 66,957 | **12** | 3.00 | Tight defensive tactical masterclasses |
| **Semi Finals** | 2 | 138,415 | 69,208 | **5** | 2.50 | France vs. Brazil, Argentina vs. England |
| **Third Place Match** | 1 | 64,478 | 64,478 | **10** | **10.00** | Thrilling high-scoring classification match |
| **World Cup Final** | 1 | 80,663 | **80,663** | **1** | 1.00 | MetLife Stadium Championship Final |
| **Total Tournament** | **104** | **5,850,744** | **56,257** | **308** | **2.96** | 16 Stadiums Across North America |

---

## 🟨 Officiating & Player Discipline Telemetry

Disciplinary telemetry across 104 matches monitored by 25 elite international match officials:

### 1. Match Official Workload & Geographic Representation
* **Total Referees:** 25 match officials from **21 distinct national associations**.
* **Average Appointments:** **4.16 matches per referee** across group and knockout rounds.
* **Marquee Appointments:** World Cup Final officiated at MetLife Stadium; opening match officiated at Estadio Azteca.

### 2. Disciplinary Infractions & Card Tracking
| Disciplinary Category | Total Count | Per Match Avg | High-Risk Impact |
| :--- | :---: | :---: | :--- |
| **Yellow Cards Issued** | **8** | 0.08 / match | Tactical fouls & cautionable challenges |
| **Red Cards Issued (Expulsions)** | **15** | 0.14 / match | Direct dismissals & severe tactical infractions |
| **Disciplined Players Logged** | **19** | N/A | High-impact suspension risk watchlist |

---

## 📐 Core DAX Measures & Formulas Reference

All analytical measures are centralized under the `DAX Measure` table:

### 1. Match Volume & Attendance Measures

#### Total Attendance & Average Match Density
```dax
total_attendance = 
SUM(fact_matches[attendance])

avg_attendance = 
DIVIDE([total_attendance], [total_matches], 0)

peak_attendance = 
MAXX(fact_matches, fact_matches[attendance])
```

#### Total Goals & Scoring Rates
```dax
total_goals = 
SUM(fact_matches[team_1_goals]) + SUM(fact_matches[team_2_goals])

goal/match = 
DIVIDE([scorer_goals], [total_matches], 0)

total_normal_goals = 
CALCULATE(
    COUNTROWS(fact_player_goals), 
    fact_player_goals[goal_type] = "Normal"
)

total_own_goals = 
CALCULATE(
    COUNTROWS(fact_player_goals), 
    fact_player_goals[goal_type] = "Own Goal"
)
```

### 2. Stadium & Infrastructure Calculations
```dax
total_stadium_capacity = 
SUM(dim_stadiums[capacity])

avg_stadium_capacity = 
AVERAGE(dim_stadiums[capacity])

largest_stadium_capacity = 
MAX(dim_stadiums[capacity])

largest_stadium_name = 
CALCULATE(
    SELECTEDVALUE(dim_stadiums[stadium_name]), 
    FILTER(dim_stadiums, dim_stadiums[capacity] = [largest_stadium_capacity])
)
```

### 3. Group Standings & Qualification Logic
```dax
group_matches_played = 
DIVIDE(SUM(fact_group_standings[pld]), 2, 0)

group_goals_scored = 
SUM(fact_group_standings[gf])

group_avg_attendance = 
AVERAGE(fact_matches[attendance])
```

---

## 🖼️ Dashboard Visual Tour & Architecture

The report contains **6 dedicated pages** and multiple analytical drill-downs:

### 1. Tournament Executive Landing Portal (`Landing Page.png`)
* Central navigation launchpad with FIFA World Cup 2026 branding, host country flags, and direct links to all operational modules.

<p align="center">
  <img src="./Dashboard%20Previews/Landing%20Page.png" width="92%" alt="Landing Page Preview" />
</p>

---

### 2. High-Level Tournament Overview (`Overview.png`)
* Executive KPI scorecard: Total Matches (`104`), Total Goals (`308`), Attendance (`5.85M`), Stadiums (`16`), and Referees (`25`).
* Goals timeline progression, attendance distribution by stage, and country breakdown.

<p align="center">
  <img src="./Dashboard%20Previews/Overview.png" width="92%" alt="Tournament Overview Preview" />
</p>

---

### 3. Group Stage Standings & Match Dynamics (`Group Stage.png`)
* Interactive group selector for Groups A through L with dynamic tables for Points, Played, Won, Drawn, Lost, GD, and Qualification status.

<p align="center">
  <img src="./Dashboard%20Previews/Group%20Stage.png" width="92%" alt="Group Stage Preview" />
</p>

---

### 4. Knockout Bracket & Tournament Tree (`Knockout Stage.png`)
* Complete bracket visualization tracking qualified teams through Round of 32, Round of 16, Quarter Finals, Semi Finals, Third Place, and the Final.

<p align="center">
  <img src="./Dashboard%20Previews/Knockout%20Stage.png" width="92%" alt="Knockout Stage Preview" />
</p>

---

### 5. Detailed Match-by-Match Telemetry (`Matches.png`)
* Comprehensive match schedule, kickoff times, venue links, referee assignments, scores, and head-to-head records.

<p align="center">
  <img src="./Dashboard%20Previews/Matches.png" width="92%" alt="Matches Preview" />
</p>

---

### 6. Player Performance, Golden Boot & Discipline (`Top Scorers.png` / `Discipline Players.png` / `Top Own Scorers.png`)
* Golden Boot race leaderboards with player cards, goals per match, club/national affiliation, disciplinary card sanctions, and own-goal tallies.

<p align="center">
  <img src="./Dashboard%20Previews/Top%20Scorers.png" width="48%" alt="Top Scorers Preview" />
  <img src="./Dashboard%20Previews/Discipline%20Players.png" width="48%" alt="Discipline Players Preview" />
</p>

---

### 7. Stadium Infrastructure & Referee Operations (`Stadiums.png` / `Referees.png`)
* Interactive venue map and cards detailing city, capacity, matches hosted, and officiating appointment workloads.

<p align="center">
  <img src="./Dashboard%20Previews/Stadiums.png" width="48%" alt="Stadiums Preview" />
  <img src="./Dashboard%20Previews/Referees.png" width="48%" alt="Referees Preview" />
</p>

---

### 8. Star Schema Model Architecture (`Model.png`)
* Full entity-relationship model linking match facts, standings, player goals, and dimensional tables.

<p align="center">
  <img src="./Dashboard%20Previews/Model.png" width="92%" alt="Model Architecture Preview" />
</p>

---

## 🏗️ Data Architecture & Star Schema Design

The data model uses a **multi-fact star schema** optimized for sports telemetry, allowing cross-stage analysis and player-to-match drill-downs:

```
                            +-----------------------+
                            |       dim_stage       |
                            +-----------------------+
                            | stage_key (PK)        |
                            | stage / stage_type    |
                            +-----------+-----------+
                                        | 1
                                        |
                                        | *
+-----------------------+ 1             |             1 +-----------------------+
|      dim_stadiums     |---------------+---------------|     dim_refereees     |
+-----------------------+               |               +-----------------------+
| stadium_key (PK)      |               |               | referee_key (PK)      |
| country / city        |               |               | referee_name          |
| stadium_name          |               |               | referee_nationality   |
| capacity              |               |               +-----------------------+
+-----------------------+               |
                                        |
                           +------------+------------+
                           |       fact_matches      |
                           +-------------------------+
                           | match_key (PK)          |
                           | group_key (FK)          |
                           | referee_key (FK)        |
                           | stadium_key (FK)        |
                           | stage_key (FK)          |
                           | team_1_key / team_2_key |
                           | match_date / kickoff    |
                           | team_1_goals / team_2   |
                           | attendance              |
                           +------------+------------+
                                        | 1
                                        |
           +----------------------------+----------------------------+
           | * (Inactive link)                                       | * (Inactive link)
+----------+------------+                                 +----------+------------+
|   fact_player_goals   |                                 |    fact_match_teams   |
+-----------------------+                                 +-----------------------+
| match_key (FK)        |                                 | match_key (FK)        |
| team_key (FK)         |                                 | team_key (FK)         |
| players_key (FK)      |                                 | side (Home/Away)      |
| goal_minute           |                                 | goals_for / against   |
| goal_type             |                                 | goal_difference       |
+----------+------------+                                 +----------+------------+
           | *                                                       | *
           |                                                         |
           | 1                                                       | 1
+----------+------------+                                 +----------+------------+
|      dim_players      |                                 |       dim_teams       |
+-----------------------+                                 +-----------------------+
| players_key (PK)      |                                 | team_key (PK)         |
| player_name           |                                 | team_name             |
| nationality           |                                 | continent             |
| player_url_pic        |                                 | team_url_pic          |
+-----------------------+                                 +-----------------------+
```

---

## ⚙️ ETL & Power Query Pipeline

The data pipeline standardizes disparate match logs and tournament assets:
1. **Match Telemetry Normalization:** Ingested raw fixture schedules, parsed kickoff times, and standardized attendance figures across all host countries.
2. **Player Goal Indexing:** Mapped every goal event with exact minute, team attribution, and classified goal types (`Normal` vs. `Own Goal`).
3. **Standings Computation:** Formatted group tables calculating Points (3 for Win, 1 for Draw), Goal Differential (`GF - GA`), and rank ordering.
4. **Digital Asset Management:** Embedded high-resolution vector and image URLs for stadium photography, player headshots, referee portraits, and national team crests.

---

## 📁 Repository Structure

```
Kerelos-Nakhla/The-Road-To-Glory/
│
├── Assets/                        # Brand wallpapers and vector iconography
├── Dashboard Previews/             # High-resolution report page screenshots
│   ├── Discipline Players.png     # Disciplinary cautions & expulsions
│   ├── Group Stage.png            # Groups A-L interactive standings
│   ├── Knockout Stage.png         # 32-team tournament knockout bracket
│   ├── Landing Page.png           # Executive navigation portal
│   ├── Matches.png                # Match-by-match schedule & results
│   ├── Model.png                  # Multi-fact Star Schema data model
│   ├── Overview.png               # High-level tournament KPI scorecard
│   ├── Referees.png               # Match official assignments & workloads
│   ├── Stadiums.png               # Venue capacities & city infrastructure
│   ├── Top Own Scorers.png        # Own goal tallies and impact analysis
│   └── Top Scorers.png            # Golden Boot leaderboard & scoring rates
│
├── Data/                          # Dimensional Excel workbooks & match facts
│   ├── dim_group.xlsx             # Group stage dimension table
│   ├── dim_players.xlsx           # Player registry & profile dimension
│   ├── dim_refereees.xlsx         # Match officials dimension table
│   ├── dim_stadiums.xlsx          # Host stadiums & capacity dimension
│   ├── dim_stage.xlsx             # Tournament stages (Group through Final)
│   ├── dim_teams.xlsx             # 48 national teams dimension table
│   ├── fact_group_standings.xlsx  # Official group stage points & records
│   ├── fact_match_teams.xlsx      # Team-level match performance fact
│   ├── fact_matches.xlsx          # Fixtures, attendance & scorelines fact
│   ├── fact_player_discipline.xlsx# Cards and disciplinary actions fact
│   └── fact_player_goals.xlsx     # Granular goal-level event fact table
│
├── LICENSE                        # MIT License
├── README.md                      # Comprehensive project documentation
└── THE ROAD TO GLORY.pbix         # Production Power BI dashboard file
```

---

## 🛠️ Tools & Technologies

* **Business Intelligence:** Microsoft Power BI Desktop (May 2024+ PBIP & TMDL Architecture)
* **Data Modeling:** Multi-Fact Star Schema with active dimensional routing and role-playing relationships
* **Analytics Engine:** DAX (Data Analysis Expressions) for goal-ratio benchmarks, attendance tracking, and dynamic group rankings
* **ETL Engine:** Power Query / M language for tabular ingestion, minute parsing, and event normalization
* **Visual Components:** Custom HTML/SVG scorecards, interactive tournament bracket views, multi-row KPI cards

---

## 📜 License & Author

Developed by **[Kerelos Nakhla](https://github.com/Kerelos-Nakhla)**  
Data Analyst & BI Developer | Power BI & Sports Analytics Specialist

* **GitHub:** [@Kerelos-Nakhla](https://github.com/Kerelos-Nakhla)
* **Email:** kerelosnakhlasaad@gmail.com

*This project is distributed under the MIT License.*
