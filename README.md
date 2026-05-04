# F1-Data-Analysis
# 🏎️ F1 Classic Era — Data Analysis Project

> **"Before Lewis Hamilton.. Before Max Verstappen.. There was another era!"**

A data analysis project exploring the classic era of Formula 1 (1950s–1990s) using MySQL and Power BI.

---

## 📖 Project Story

As an F1 fan learning Data Analysis, I asked myself:
**What did Formula 1 look like before the drivers we know today?**

I decided to travel back in time and analyze the classic era of F1 — a period most of us don't know much about. A time when Ferrari and Maserati battled every race, British drivers dominated the championship, and Monza & Monaco were the kings of circuits.

---

## 📊 Dataset

- **Source:** [Kaggle — Formula 1 World Championship Dataset](https://www.kaggle.com)
- **Coverage:** 1950 – 2026
- **Size:** 25,000+ race results across 8 tables

| Table | Description |
|---|---|
| f1_results | All race results |
| f1_drivers | Driver information |
| f1_races | Race details |
| f1_circuits | Circuit information |
| f1_constructors | Team information |
| f1_driver_standings | Driver standings per season |
| f1_constructor_standings | Constructor standings per season |
| f1_qualifying | Qualifying results |

---

## 🛠️ Tools Used

- **MySQL** — Database creation, data import, SQL queries
- **Power BI** — Interactive dashboard (5 pages)

---

## 🔍 SQL Queries

11 queries covering:

1. Top 10 winning drivers
2. Top 10 winning teams
3. Total drivers in dataset
4. Circuits by country
5. Season with most races
6. Most used circuits (without JOIN)
7. Most used circuits (with JOIN)
8. Team points per season
9. Winning drivers with nationality (JOIN)
10. Top winning nations
11. Season races with circuit details (JOIN)

---

## 📈 Key Findings

- 🏆 **Jackie Stewart** — Most wins in this dataset (27 wins)
- 🔴 **Ferrari** — Most successful constructor (80+ wins)
- 🇬🇧 **Britain** — Most wins by nationality
- 🏁 **Autodromo Nazionale di Monza** — Most used circuit (76 races)

---

## 📊 Power BI Dashboard

5-page interactive dashboard:

| Page | Content |
|---|---|
| Overview | KPIs, top drivers, top teams, circuits map |
| Drivers | Driver wins over seasons, nationality analysis |
| Teams | Constructor wins, points over seasons |
| Circuits | Most used circuits, treemap, map |
| Credits | Project summary |

---

## 🗂️ Project Structure

```
F1-Data-Analysis/
│
├── f1_sql_queries.sql       # All 11 SQL queries
├── README.md                # Project documentation
└── dashboard/
    └── screenshots/    https://drive.google.com/drive/folders/1T7nCaCJLKFBPkilhjS1vf74zEB5fN2WE     # Dashboard screenshots
```

---

## 👤 Author

**Omar Fayez**
- LinkedIn: [Your LinkedIn]
- GitHub: [Your GitHub]

---

*"Data is not just numbers — it's history waiting to be told!"* 📖
