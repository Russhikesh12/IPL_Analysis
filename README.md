# 🏏 IPL Historical Trends & Records

An end-to-end data analytics project analyzing 10+ years of IPL data 
to uncover historical trends, records, and insights.

## 📊 Live Dashboard
👉 [View Tableau Dashboard](<https://public.tableau.com/app/profile/russhikesh.patil/viz/Sports_analysis_Cricket/IPLHISTORICALTRENDSANDRECORDS?publish=yes>)

## 📁 Project Structure
```
IPL-Analytics/
│
├── data/
│   ├── matches.csv
│   ├── deliveries.csv
│   ├── matches_cleaned.csv
│   ├── deliveries_cleaned.csv
│   └── merged_data.csv
│
├── tableau/
│   ├── tableau_team_wins.csv
│   ├── tableau_toss_trends.csv
│   ├── tableau_top_batsmen.csv
│   ├── tableau_top_bowlers.csv
│   └── tableau_venues.csv
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   └── sql_analysis.ipynb
│
├── ipl.db
└── README.md
```

## 🔍 Key Questions Answered
- Which teams have dominated IPL across seasons?
- Does winning the toss impact match outcome?
- How has batting strategy evolved over the years?
- Who are the all-time top run scorers and wicket takers?
- Which venues host the most matches?

## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| Python + Pandas | Data cleaning & EDA |
| Matplotlib + Seaborn | Visualizations |
| SQLite + SQL | Data storage & querying |
| Tableau Public | Interactive dashboard |

## 📌 Key Insights
- **Mumbai Indians** are the most successful IPL team with 130+ wins
- Teams winning the toss **choose to field ~65%** of the time
- **V Kohli** is the all-time leading run scorer in IPL history
- **YS Chahal** leads all-time wicket takers
- **Eden Gardens** is the most used IPL venue

## 🚀 How to Run
1. Clone the repo
```bash
   git clone https://github.com/<Russhikesh12>/IPL-Analytics.git
```
2. Install dependencies
```bash
   pip install pandas numpy matplotlib seaborn sqlalchemy jupyter
```
3. Run notebooks in order:
   - `data_cleaning.ipynb`
   - `eda.ipynb`
   - `sql_analysis.ipynb`

## 📂 Data Source
- [IPL Complete Dataset - Kaggle](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)

## 👤 Author
**Rushikesh** — Aspiring Data Analyst and Product Manager | IT Engineering Student @ MMCOE Pune
