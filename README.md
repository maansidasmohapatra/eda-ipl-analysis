# IPL Match Data — Exploratory Data Analysis

## Overview
Exploratory Data Analysis on IPL match data from 2008 to 2019,
covering 756 matches across 12 seasons. The goal is to uncover
patterns in team performance, toss decisions, match outcomes,
and player dominance using Python visualizations.

## Dataset
- **Source:** Kaggle IPL Dataset
- **File:** matches.csv
- **Rows:** 756
- **Columns:** 18
- **Seasons Covered:** IPL 2008 — IPL 2019

## Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Analysis Performed
- Team win counts across all seasons
- Toss decision distribution (bat vs field)
- Correlation between toss winner and match winner
- Top 10 cities by matches hosted
- Matches played per season trend
- Top 10 Player of the Match winners
- Win margin distribution (by runs and by wickets)

## Key Findings
- Mumbai Indians lead with 109 wins, followed by Chennai Super Kings (100) and Kolkata Knight Riders (92)
- Teams heavily prefer fielding after winning the toss — 463 field vs 293 bat decisions
- Winning the toss does not strongly predict winning the match
- Mumbai hosted the most matches (101), followed by Kolkata (77) and Delhi (74)
- CH Gayle (21), AB de Villiers (20), and MS Dhoni (17) are the top Player of the Match winners

## How to Run
1. Open `IPL_EDA.ipynb` in Google Colab
2. Upload `matches.csv` when prompted
3. Run all cells in order
