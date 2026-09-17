# ⚽ THE ROAD TO GLORY — FIFA World Cup 2026

> **FIFA WORLD CUP 2026 — DATA EXPERIENCE**

An interactive football analytics experience built around the **FIFA World Cup 2026**.

This project goes beyond a conventional Power BI dashboard. It combines **data analytics, interactive storytelling, custom HTML/CSS, and football-inspired visual design** to turn tournament data into a cinematic data experience.

---

## 🎯 Project Vision

**The Road to Glory** was designed to answer more than *"What does the data say?"*

It explores:

- How the tournament is structured
- How teams progress from the group stage to the final
- Where the tournament is played
- Which players stand out
- How matches unfold
- How goals and discipline shape the tournament
- How raw football data can become an engaging analytical experience

The objective was to build something closer to a **FIFA / ESPN-style match and tournament experience** than a traditional BI report.

---

## 📊 Tournament at a Glance

| Metric | Value |
|---|---:|
| 🌍 Teams | **48** |
| ⚽ Matches | **104** |
| 🥅 Goals | **308** |
| 🏟️ Stadiums | **16** |
| 📅 Group-Stage Matches | **72** |
| 🏆 Knockout Matches | **32** |
| 👤 Player Goal Records | **195** |
| 🟨 Discipline Records | **19** |

All headline figures are calculated from the project datasets rather than manually hard-coded into the analytical logic.

---

## 🔄 End-to-End Data Workflow

```text
Web Sources
    ↓
Data Collection
    ↓
Python + Beautiful Soup
    ↓
Raw Tournament Data
    ↓
Pandas
    ↓
Cleaning & Transformation
    ↓
Power BI Data Model
    ↓
DAX Measures
    ↓
HTML + CSS
    ↓
Interactive FIFA World Cup 2026
Data Experience
```

---

## 🛠️ Tech Stack

### 🐍 Python
Used for data collection and preparation.

- Python
- Beautiful Soup
- Pandas

### 📊 Power BI
Used as the analytical layer for:

- Data modeling
- Relationships
- Measures
- KPIs
- Filtering
- Tournament analysis
- Interactive navigation

### 🧮 DAX
Used to create dynamic analytical calculations, including tournament KPIs, player statistics, match analysis, stage-level calculations, and cumulative metrics.

### 🎨 HTML & CSS
Custom HTML/CSS components were used to move the project beyond standard Power BI visuals and create a more immersive interface.

---

## 🗂️ Data Model

The project is built around dedicated tournament datasets:

- `Teams.xlsx`
- `Matches.xlsx`
- `Stadium.xlsx`
- `Players.xlsx`
- `Group & Knockout.xlsx`

The datasets cover teams, matches, stadiums, players, goals, discipline, groups, and knockout-stage progression.

The player dataset also contains non-player note rows, which are excluded from player-level analysis.

---

## 🏆 Tournament Structure

The tournament experience follows the complete World Cup journey:

```text
GROUP STAGE
    ↓
ROUND OF 32
    ↓
ROUND OF 16
    ↓
QUARTER-FINALS
    ↓
SEMI-FINALS
    ↓
FINAL
    ↓
🏆 CHAMPION
```

The knockout experience supports match outcomes including **extra time (AET)** and **penalty shootouts (PEN)** where applicable.

---

## 🖥️ Experience Sections

### 🏠 Intro

A cinematic entry point introducing the **Road to Glory** concept and guiding users into the tournament experience.

### 📈 Tournament Pulse

A high-level analytical view of the tournament with dynamic KPIs and tournament statistics.

### 🏟️ World's Stages

An exploration of the **16 stadiums** hosting the tournament, connecting venue information with the tournament story.

### ⚽ Match Center

A match-focused experience covering tournament fixtures, results, stages, and match details.

The match experience can surface a goal timeline and detailed match information rather than presenting matches as a simple static table.

### 🛣️ Road to Glory

A visual tournament journey from the **12 groups** through the knockout stages to the final.

The bracket follows:

**Groups A–L → R32 → R16 → QF → SF → Final**

### ⭐ Stars

A player-focused section highlighting scoring and discipline information.

The experience separates:

- **Top Scorers**
- **Discipline**

---

## 📌 Analytical Focus

The project explores several dimensions of the tournament:

### Teams
- Team participation
- Group allocation
- Tournament progression
- Stage performance

### Matches
- Fixtures
- Results
- Tournament stages
- Goals
- Extra time
- Penalty shootouts

### Players
- Goals
- Scoring contribution
- Top scorers
- Player-level tournament statistics

### Stadiums
- Stadium information
- Locations
- Tournament venues

### Tournament Progression
- Groups A–L
- Round of 32
- Round of 16
- Quarter-finals
- Semi-finals
- Final

### Discipline
- Player discipline
- Cards and related tournament records

---

## 🎨 Design Philosophy

The main design goal was to create a **data experience**, not simply a dashboard.

The visual direction takes inspiration from:

- FIFA tournament experiences
- ESPN match centers
- DAZN-style sports interfaces
- Broadcast graphics
- Modern data journalism

The interface uses:

- Cinematic football visuals
- Strong typography
- Custom KPI components
- Interactive navigation
- Tournament brackets
- Match cards
- Player tables
- Goal timelines
- Progress indicators
- HTML/CSS components
- Motion and interaction where appropriate

The design prioritizes **storytelling, hierarchy, and exploration** while keeping the underlying analytics dynamic.

---

## 🧠 Key Data Analytics Challenges

### Dynamic Tournament Calculations

Tournament statistics are calculated from the underlying data model so that the experience can respond to filters and selections.

### Match Ordering

Where exact goal timestamps are unavailable, cumulative goal analysis follows the **tournament stage and match order** instead of assuming unavailable minute-level information.

### Knockout Logic

The tournament structure accounts for different match outcomes, including:

- Regular-time wins
- Extra-time wins (**AET**)
- Penalty shootouts (**PEN**)

### Data Cleaning

Web-collected data required preprocessing before being loaded into the analytical model.

Pandas was used to:

- Clean raw records
- Standardize fields
- Structure datasets
- Handle inconsistencies
- Prepare analysis-ready tables

---

## 🚀 What This Project Demonstrates

This project demonstrates an end-to-end analytics workflow:

**Data Collection → Data Cleaning → Data Modeling → DAX → Visualization → Interactive Experience**

It combines technical analytics skills with **data storytelling and UI/UX thinking**.

### Skills Demonstrated

- Python
- Web Scraping
- Beautiful Soup
- Pandas
- Data Cleaning
- Data Modeling
- Power BI
- DAX
- Data Visualization
- HTML
- CSS
- Dashboard UX/UI
- Data Storytelling
- Interactive Analytics

---

## 📁 Project Structure

```text
The-Road-To-Glory/
│
├── Data/
│   ├── Teams.xlsx
│   ├── Matches.xlsx
│   ├── Stadium.xlsx
│   ├── Players.xlsx
│   └── Group & Knockout.xlsx
│
├── Python/
│   └── Web scraping & data preparation
│
├── Power BI/
│   └── Analytical model & report
│
├── Assets/
│   └── Visual resources
│
└── README.md
```

> Folder names may vary from the current repository structure; the structure above describes the intended organization of the project components.

---

## 📚 Data Source

The tournament information was collected from publicly available web sources, including **Wikipedia**, using Python web scraping.

**Primary source:**

🔗 [FIFA World Cup 2026 — Wikipedia](https://en.wikipedia.org/wiki/2026_FIFA_World_Cup)

The scraped information was subsequently cleaned and transformed before being used for analysis.

---

## 🎓 Project Context

**The Road to Glory** is part of my portfolio as a **Data Analyst / BI Developer** and was developed to demonstrate how analytics can be presented as an interactive product rather than a collection of charts.

The project focuses on the complete journey from **raw web data to a polished analytical experience**.

---

## 👤 Author

**Kerelos Nakhla Saad**

**Data Analyst | BI Developer**

- GitHub: [Kerelos-Nakhla](https://github.com/Kerelos-Nakhla)
- LinkedIn: [Kerelos Nakhla](https://www.linkedin.com/in/kerelos-nakhla/)

---

⭐ If you find the project interesting, feel free to explore the repository and the other analytics projects on my GitHub.
