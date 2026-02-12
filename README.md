# ⚾ Moneyball Analytics: OBP, Player Similarity, and Team Chemistry

![Python](https://img.shields.io/badge/Python-Data%20Science-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Clustering-F7931E?logo=scikitlearn&logoColor=white)
![MDS](https://img.shields.io/badge/Multidimensional-Scaling-6A1B9A)
![K-Means](https://img.shields.io/badge/K--Means-Clustering-0A66C2)
![Network Analysis](https://img.shields.io/badge/Graph-Network%20Analysis-00897B)
![Sports Analytics](https://img.shields.io/badge/Sports-Moneyball%20Analytics-2E7D32)
![Statistical Modeling](https://img.shields.io/badge/Statistical-Modeling-795548)
![Data Visualization](https://img.shields.io/badge/Data-Visualization-FF7043)

## 📌 Project Overview
This project analyzes how the Moneyball philosophy exploited inefficiencies
in Major League Baseball by focusing on undervalued metrics and structural factors.

We explore:
- Whether traditional Moneyball metrics still provide competitive advantages
- How player similarity can be identified using multidimensional scaling (MDS)
- Whether team chemistry and experience influence winning outcomes

---

## ❓ Research Questions
- **RS1:** To what extent have traditional Moneyball metrics (OBP) lost their competitive advantage?
- **RS2:** Can Multidimensional Scaling (MDS) identify statistically similar "doppelgänger" players?
- **RS3:** Do intangible factors such as team chemistry and experience impact win rates?

---

## 📊 Data Sources
- Lahman Baseball Database (Kaggle)
- Files used:
  - batting.csv
  - pitching.csv
  - teams.csv
  - salary.csv
  - master.csv

---

## 🧠 Methods
### RS1 – Team-Level Analysis
- Team OBP calculation
- OBP vs runs scored
- Salary efficiency comparison (Moneyball era focus: 2002)

### RS2 – Player Similarity
- Metrics: OBP, SLG, ISO, Walk Rate
- Standardization and K-Means clustering
- Multidimensional Scaling (MDS) using Euclidean distance
- Visualization with salary-scaled points

### RS3 – Team Chemistry & Experience
- Chemistry index based on shared playing seasons
- Network graph analysis (Fruchterman–Reingold algorithm)
- Average age vs win rate comparison

---

## 📈 Key Findings
- OBP remains a stable and strong predictor of run production
- Players with similar offensive profiles can have drastically different salaries
- Team experience shows the strongest correlation with championship success
- Chemistry contributes to performance but is not solely decisive

---

## 📁 Repository Structure
- `report/` – Final written report (PDF)
- `data/` – Raw datasets
- `notebooks/` – Analysis notebooks
- `visuals/` – Key charts and figures

---

## Contributors & Responsibilities

- **Hyuntae Park**
  - Team OBP & salary efficiency analysis
  - Player similarity modeling (MDS, clustering)
  - Data preprocessing and visualization

- Moksh Goel
  - Team chemistry index design
  - Network graph analysis

- Aditi Vedak
  - Exploratory analysis and report structuring

---

```
moneyball-analytics-project/
│
├── README.md
│
├── report/
│   └── Moneyball_Analytics_Report.pdf
│
├── data/
│   ├── batting.csv
│   ├── pitching.csv
│   ├── teams.csv
│   ├── salary.csv
│   └── master.csv
│
├── notebooks/
│   ├── obp_team_analysis.ipynb
│   ├── player_similarity_mds.ipynb
│   └── chemistry_network_analysis.ipynb
│
├── visuals/
│   ├── obp_vs_runs.png
│   ├── mds_similarity_map.png
│   ├── chemistry_vs_winrate.png
│   └── experience_vs_winrate.png
│
└── requirements.txt
```
