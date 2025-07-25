# 🏏 IPL Data Analysis (EDA) - Project README

Welcome to the IPL Cricket Data EDA repository!
This project provides a complete Exploratory Data Analysis (EDA) pipeline on Indian Premier League (IPL) datasets, offering actionable insights into player performances, team trends, and key T20 cricket metrics.

===================================================================
📑 Table of Contents
- Project Overview
- Dataset Description
- Requirements
- Usage
- Analysis Workflow
- Key Features
- Visualization Examples
- Contributing
- License

===================================================================
🔍 Project Overview
This repository contains code and sample data to perform in-depth analysis of IPL player and match statistics.
The analysis includes:
- Data cleaning and preprocessing
- Feature engineering
- Trend visualizations
- Correlation heatmaps
- Cricket-specific performance metrics for decision-making and evaluation

===================================================================
📂 Dataset Description
File: cricket_data.csv
Seasons Covered: IPL 2008 – IPL 2024

Key Attributes:
- Year, Player Name
- Batting & Bowling Statistics
- Fielding metrics (Catches, Stumpings)
- Advanced cricket metrics:
  - Runs, Wickets, Strike Rate
  - Centuries, Boundaries
  - Economy rate, Bowling average

===================================================================
💻 Requirements
- Python 3.7+
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn (for normalization)
  - scipy (for z-score calculations)
  - Jupyter Notebook (optional for interactive use)

Install dependencies using:
pip install pandas numpy matplotlib seaborn scikit-learn scipy

===================================================================
🚀 Usage

1. Clone the Repository:
git clone https://github.com/assistansirit2255/eda_cricket_data.git
cd eda_cricket_data

2. Run Analysis:
- Open project2.ipynb in Jupyter Notebook
- OR run the Python scripts for EDA and visualizations

3. Data:
- Dataset: cricket_data.csv (already included)

===================================================================
🔄 Analysis Workflow

1. Data Cleaning & Preprocessing
- Remove "No stats" entries
- Handle missing values
- Convert data types
- Deduplicate player-season entries
- Detect outliers

2. Feature Engineering
- Boundary % (runs from 4s & 6s)
- Batting Impact Score (runs, average, SR)
- All-rounder Score (batting + bowling combined)
- Player categorization (based on strike rate/performance)

3. EDA
- Distribution plots (avg, SR, economy)
- Player trend analysis (runs/wickets over seasons)
- Top performer detection (most centuries/wickets)
- Correlation heatmaps

4. Visualizations
- Bar Charts: Runs vs Balls
- Line Charts: Yearly Performance Trends
- Pie Charts: Centuries vs Half-centuries
- Scatter Plots: Bowling Avg vs Bowling SR

5. Python Queries (like SQL)
- Top averages
- Most matches
- 500+ run seasons
- 5-wicket hauls

===================================================================
⭐ Key Features
- Cleaned & structured IPL data (2008–2024)
- Custom performance metrics for batting/bowling
- Pre-built EDA pipeline in Python
- Visualizations for key player insights
- Ready-to-run in Jupyter or standalone scripts

===================================================================
📊 Visualization Examples
Includes:
- Histograms, bar charts, line graphs
- Pie charts and scatter plots
- Correlation heatmaps
- Player-wise trend graphs

===================================================================
🤝 Contributing
We welcome contributions!
- Fork the repo
- Add your features/fixes
- Submit a Pull Request

Suggestions for improvements or new metrics are always appreciated.

===================================================================
📄 License
This project is open-source and available under the MIT License.

===================================================================
👨‍💻 Built with ❤️ for Data, Cricket, and Python.

