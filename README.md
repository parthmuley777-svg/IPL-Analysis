# 🏏 IPL — Most Runs Analysis

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Colab](https://img.shields.io/badge/Google%20Colab-Notebook-yellow?style=for-the-badge&logo=googlecolab)
![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge)

> A complete **Exploratory Data Analysis (EDA)** project on the Indian Premier League's all-time top run-scorers, built and run on **Google Colab**.

---

## 📌 Project Overview

This project analyzes the batting statistics of the **top run-scorers in IPL history** (2008–2025). It uncovers insights about player performance, boundary hitting, career longevity, team contributions, and more — all through rich visualizations and a custom composite batting rating system.

---

## 📂 Dataset

| File | Description |
|------|-------------|
| `Most_runs_in_Indian_Premier_League.csv` | Top IPL run-scorers with full batting stats |

### Columns in Dataset

| Column | Description |
|--------|-------------|
| `player` | Player name with team abbreviation |
| `span` | Career span (e.g. 2008–2025) |
| `playing_team` | Teams played for |
| `matches` | Total matches played |
| `innings` | Total innings batted |
| `not_out` | Number of not-out innings |
| `runs` | Total runs scored |
| `strike_rate` | Batting strike rate |
| `average` | Batting average |
| `balls_faced` | Total balls faced |
| `highest_score` | Highest individual score |
| `hundreds` | Number of centuries |
| `fifties` | Number of half-centuries |
| `ducks` | Number of ducks (0 runs) |
| `fours` | Total fours hit |
| `sixes` | Total sixes hit |

---

## 🔍 Analysis Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | Data Loading | Upload & read CSV in Colab |
| 2 | Data Cleaning | Handle nulls, fix types, engineer features |
| 3 | Top Run-Scorers | Bar chart of all-time top 15 |
| 4 | Strike Rate vs Average | Bubble scatter with player classification |
| 5 | Boundary Analysis | Fours vs Sixes, six-hitters, boundary run % |
| 6 | Hundreds & Fifties | Century & fifty leaderboard |
| 7 | Ducks Analysis | Most ducks & duck rate % |
| 8 | Career Span | Gantt timeline + longevity vs runs |
| 9 | Team Analysis | Runs & strike rate by primary team |
| 10 | Correlation Heatmap | Relationship between all batting stats |
| 11 | Player Comparison | Side-by-side comparison of any two players |
| 12 | Distribution Plots | SR, Average, Era-wise boxplot |
| 13 | Composite Rating | Custom weighted batting score (0–100) |
| 14 | Key Insights | Auto-printed summary of all findings |

---

## 📊 Key Insights

- 👑 **Virat Kohli** leads with **8,661 runs** — the highest ever in IPL history
- 💥 **Andre Russell** has the highest strike rate among top scorers
- 🏏 **Jos Buttler** has the most centuries (7) among active foreign players
- 💥 **Chris Gayle** holds the record for most sixes
- 📅 **MS Dhoni** has the longest active IPL career span
- 🎯 Most top batsmen score **45–55%** of their runs via boundaries

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.10+ | Core programming language |
| Pandas | Data manipulation & analysis |
| NumPy | Numerical computations |
| Matplotlib | Static visualizations |
| Seaborn | Statistical plots |
| Scikit-learn | MinMaxScaler for composite rating |
| Google Colab | Cloud notebook environment |

---

## 🚀 How to Run

### Option 1 — Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com)
2. Upload `IPL_Most_Runs_Analysis.ipynb`
3. Run **Step 2** — upload the CSV when prompted
4. Click **Runtime → Run All**

### Option 2 — Local (Jupyter Notebook)
```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/IPL-Most-Runs-Analysis.git
cd IPL-Most-Runs-Analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# Launch Jupyter
jupyter notebook IPL_Most_Runs_Analysis.ipynb
```

---

## 📁 Project Structure

```
IPL-Most-Runs-Analysis/
│
├── IPL_Most_Runs_Analysis.ipynb   # Main Colab notebook
├── Most_runs_in_Indian_Premier_League.csv  # Dataset
└── README.md                      # Project documentation
```

---

## 📈 Sample Visualizations

| Chart | What it shows |
|-------|--------------|
| 🏆 Top 15 Run-Scorers | Horizontal bar chart of all-time leaders |
| ⚡ SR vs Average Bubble Plot | Player batting style classification |
| 📅 Career Gantt Chart | Visual career timelines of top 20 |
| 🔥 Correlation Heatmap | How batting stats relate to each other |
| 🏅 Composite Rating | Overall batting quality score out of 100 |

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add more seasons of data
- Build an interactive Plotly/Streamlit dashboard
- Add bowling or fielding datasets
- Improve the composite rating formula

---

## 📜 License

This project is licensed under the **MIT License** — free to use and modify.

---

## 👨‍💻 Author

Made with ❤️ and 🏏 by Parth Muley
