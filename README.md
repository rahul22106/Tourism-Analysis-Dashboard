# 🌍 Tourism Analysis Dashboard — Power BI

> **Solving low tourism through data** — analyzing 52,930 visits across 30 attractions, 164 countries, and 10 years to identify the root causes of decline and deliver a data-backed recovery strategy.

---

## 📌 Problem Statement

Tourism collapsed **96%** in 2020 (5,913 → 529 visits). Recovery by 2022 reached only 247 visits — 95.8% below baseline. This project identifies **why** and prescribes **exactly what to do**.

---

## 💡 Key Insights That Drive the Solution

| Finding | Data | Action |
|---|---|---|
| Couples dominate travel | 40.8% of all visits | Target August peak with couple packages |
| Single attraction risk | Monkey Forest = 25% of visits | Redirect to Waterbom Bali (4.65★, 6,429 visits) |
| 2 markets drive majority | Australia 25% + Asia 29.6% = 55% | Focus marketing budget here first |
| Off-season gap | February = 3,671 vs August = 5,026 | Off-season promotions to smooth revenue |
| Hidden gems undermarketed | Mt. Semeru 4.70★ — barely known | Promote highest-rated, not most-visited |

---

## 📊 Dashboard Pages

| Page | Focus |
|---|---|
| 1 — Overview | Executive summary with KPIs and navigation |
| 2 — Attraction Analysis | What they visit, ratings vs volume |
| 3 — Time & Behavior | When they travel, peak seasons, travel mode |
| 4 — Ratings & Satisfaction | Satisfaction scoring, best vs worst attractions |


## 🔧 Tech Stack

- **Power BI Desktop** — dashboard and visualizations
- **Power Query** — data cleaning and transformation
- **DAX** — calculated columns and measures
- **TopoJSON** — custom Shape Map for geographic analysis

---

## ⚡ Quick Start

1. Clone the repo
2. Open `Tourism_Dashboard.pbix` in Power BI Desktop
3. If prompted, update data source paths to your local `/data` folder
4. Load the `custom_geo.json` file in the Shape Map visual settings

---

## 📈 Dataset Overview

| Metric | Value |
|---|---|
| Total Visits | 52,930 |
| Unique Visitors | 33,530 |
| Attractions | 30 |
| Countries | 164 |
| Period | 2013 – 2022 |
| Avg Rating | 4.16 / 5 |
| Repeat Visitor Rate | 31.7% |

---

## 🎯 Resume Bullets

> **Solved 96% COVID tourism collapse** by identifying Couples (40.8%) as the #1 segment and designing targeted August peak-season packages to drive recovery.

> **Eliminated single-attraction dependency risk** by redirecting marketing to Waterbom Bali (4.65★, 6,429 visits), diversifying revenue across 30 attractions.
