---

# 🎮 Steam Market Analysis – Top 1500 Games (2024)

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-orange?logo=tableau)
![DataAnalysis](https://img.shields.io/badge/Data-Analysis-green)

## 📌 Project Overview

This project analyzes the **top 1500 games released on Steam** between **Jan 1, 2024 – Sept 9, 2024**, aggregated from 30 separate files into a single dataset. The objective is to provide **market penetration insights** for indie developers who want to launch their first commercial title.

The analysis focuses on **game design, pricing, and release strategy** to minimize risks and maximize success in an increasingly competitive market.

🔗 **Links & References**

* [Dataset on Kaggle](#) – 📊 Top 1500 Games on Steam by Revenue (2024-09-09)
* [Deployed Dashboard](#) – 🌐 Public Tableau Dashboard

---

## 📊 Dataset Breakdown

### 📝 Overview

The dataset contains **comprehensive metadata, performance, and engagement data** about Steam titles. It includes:

* **Game Details:** Title, release date, publisher/developer info
* **Sales & Revenue:** Copies sold, revenue, price points
* **Player Engagement:** Avg. playtime, peak players
* **Reviews & Scores:** User/critic ratings
* **Dynamic Market Data:** Sales rank, pricing trends

### 📂 Columns

| Column           | Description                         |
| ---------------- | ----------------------------------- |
| `name`           | Title of the game                   |
| `releaseDate`    | Official release date               |
| `copiesSold`     | Total units sold                    |
| `price`          | Original retail price               |
| `revenue`        | Total revenue generated             |
| `avgPlaytime`    | Avg. duration players spend in-game |
| `reviewScore`    | User/critic review score            |
| `publisherClass` | Publisher type (AAA / AA / Indie)   |
| `publishers`     | Publisher name                      |
| `developers`     | Developer(s)                        |
| `steamId`        | Steam’s unique game identifier      |

---

## 🎯 Problem Statement

**Case Study – Gaming Market Penetration**
With indie successes like *Palworld* and *Lethal Company*, this project aims to **help an indie studio design and launch their first commercial title**.

### Business Goal

Develop a **data-driven pre-launch playbook** that maximizes the chances of commercial success by identifying:

* Optimal **game length and playtime**
* Target **price range and revenue per copy**
* Best **release window (month/season)**
* Features that align with **high review scores**

### SMART Objectives

* **Specific:** Identify traits (price, content, timing) of successful indie games.
* **Measurable:**

  * ≥ 120,000 copies sold
  * Revenue per copy ≥ \$8
  * Review score ≥ 80%
* **Achievable:** Scope game playtime, pricing, and release window to match top indie performers.
* **Relevant:** Directly supports indie publisher entry strategy.
* **Time-Bound:** 9-month roadmap (3 weeks for predictive insights, 4 weeks for strategy, 6 months for development, 3 months post-launch tracking).

---

## 🔎 Key Questions (5W+1H Framework)

* **What** factors drive copies sold and positive reviews?
* **What** is the avg. review score by game length (short / medium / long)?
* **What** is the revenue-per-copy range among top indie titles?
* **When** are the best months to release a new game?
* **How** correlated is avg. playtime with review score?
* **How** can we scope our debut to match top 25% performers?

---

## 🧠 Analysis Approach

* Exploratory Data Analysis (EDA) of **sales, pricing, and engagement metrics**
* Comparative study of **indie vs AAA/AA performance**
* Correlation analysis: playtime ↔ review scores, price ↔ revenue-per-copy
* Seasonal trend analysis of release success
* Market segmentation of indie titles by performance quartiles

---

## 🚀 Deployment

The insights are presented in a **Tableau Dashboard**, making it easy for stakeholders to:

* Explore sales and review distributions
* Compare indie vs AAA/AA benchmarks
* Identify optimal release windows
* Simulate pricing/revenue scenarios

---

## 📂 Repository Structure

```
📦 steam-market-analysis
 ┣ 📜 steam_games_2024_dataset.csv                          # Dataset (raw)
 ┣ 📜 steam_games_2024_dataset_clean.csv                    # Dataset (processed)
 ┣ 📜 indie-gaming-market-penetration-analysis.ipynb        # Jupyter notebooks for EDA
 ┣ 📜 README.md                                             # Project documentation
```

---

## 🛠️ Tech Stack

* **Language:** Python 3.10
* **Libraries:** pandas, numpy, matplotlib, seaborn
* **Visualization:** Tableau (Interactive Dashboard)
* **EDA & Modeling:** Jupyter Notebook

---

## 📈 Insights & Outcomes

* **High-performing indie titles** tend to offer strong value (avg. playtime vs price).
* **Revenue per copy** stabilizes in the **\$8–\$12 range** for successful indie games.
* **Seasonal release timing** significantly impacts copies sold.
* **Playtime length** is moderately correlated with review scores, influencing word-of-mouth and long-term retention.

---

## 🙌 Acknowledgements

* Dataset: [Kaggle – Steam Top 1500 Games by Revenue](#)
* Deployment: Tableau Public

---
