# Top-IPL-Run-Scorers-Analysis

## 📌 Project Overview
This project analyzes the top run scorers in each Indian Premier League (IPL) season from 2008 to 2019. Using SQL queries, we extract the highest run scorer per season from match and delivery datasets, and visualize the results with charts for better understanding.

## 🗂 Dataset
The dataset contains IPL match and ball-by-ball delivery details:
- **Matches dataset** – Season, match ID, and match details
- **Deliveries dataset** – Ball-by-ball runs scored by each batsman

## 🛠 Tools & Technologies
- **SQL** – Data extraction and aggregation
- **Excel** – Data cleaning and chart creation
- **Python / Pandas** *(optional for extended analysis)*
- **Matplotlib / Excel Charts** – Visualization

## 📊 Methodology
1. **Data Extraction**: SQL query to calculate total runs for each batsman in a season.
2. **Ranking**: Use `ROW_NUMBER()` to identify the top scorer per season.
3. **Visualization**: Bar chart showing total runs of each season's top scorer.
ORDER BY
    season DESC;

