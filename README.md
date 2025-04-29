# 🏀 EuroLeague Player Stats – Scraping, Cleaning & Visualization

This project collects, processes, and visualizes EuroLeague player and team stats from 2016–2025 using web scraping and Tableau.

## 🔍 Project Purpose

The aim was to practice web scraping and data preparation using real-world data, while also reimagining how EuroLeague stats could be presented in a more intuitive and useful way than the official site offers.

## 📦 What’s Included

- **Python notebooks** for scraping player, team, and game data from the official EuroLeague site.
- **Cleaning and transformation** steps to handle missing data, team suspensions (e.g., Russian teams in 2022), and multi-team seasons.
- **Raw JSON** and **processed CSV** files (excluded via `.gitignore`) to separate scraped content from final analysis-ready data.
- A **Tableau dashboard** to interactively explore players' performance and rankings.

## 📊 Dashboard Features

> View: [Tableau Public Dashboard](https://public.tableau.com/app/profile/emre.sahin1866/viz/EuroLeaguePlayerPerformanceswithTeamSeasonandRankingComparisons/Dashboard)

- Scatter plot of PIR per game vs. minutes played
- Line chart of key season-by-season metrics
- Radar chart for percentile rankings 
- Team success tooltips, season result filters, and multi-season comparisons

## 🛠 Tools Used

- **Python** (Jupyter Notebooks)
- **Libraries**:
  - `requests`, `json`, `time`, `random` – for web scraping
  - `pandas`, `numpy`, `re` – for data cleaning and manipulation
  - `matplotlib.pyplot`, `seaborn` – for visualization
- **Output**: `.json` (scraped), `.csv` (cleaned for Tableau)
- **Visualization**: Tableau

## ⚠️ Notes

- Seasons include **COVID cancellation in 2020** and **Russian team suspensions in 2022**
- Data files are ignored from version control to comply with ethical scraping
- Dashboard and analysis are for educational and non-commercial use only

## 📬 Contact

- LinkedIn: [Emre Şahin](https://www.linkedin.com/in/emre-sahin-data/)
- GitHub: [airsahin](https://github.com/airsahin)