# 📈 Cryptocurrency Trader Performance Analysis Using Bitcoin Market Sentiment

> An end-to-end Python data analytics project that investigates the relationship between Bitcoin market sentiment and cryptocurrency trader performance using historical Hyperliquid trading data.

---

## 📌 Project Overview

Cryptocurrency markets are highly influenced by investor sentiment. During periods of **Fear**, **Neutral**, **Greed**, and **Extreme Greed**, traders often adjust their trading strategies, risk appetite, and position sizes.

This project combines the **Bitcoin Fear & Greed Index** with **historical Hyperliquid trading data** to analyze how different market conditions influence trader profitability and behavior.

The project demonstrates a complete data analytics workflow including **data cleaning, preprocessing, feature engineering, exploratory data analysis (EDA), visualization, and business insight generation using Python.**

---

# 🚀 Project Highlights

- Analyzed **2,00,000+ cryptocurrency trading records**
- Integrated two independent datasets using **Python and Pandas**
- Performed **data cleaning, timestamp conversion, and feature engineering**
- Created **10 analytical visualizations** using Matplotlib and Seaborn
- Evaluated trader performance using sentiment-based KPIs
- Generated actionable business insights and strategy recommendations

---

# 🎯 Business Problem

Can market sentiment explain changes in cryptocurrency trader performance and behavior?

This project aims to answer the following questions:

- Does trader profitability vary across different market sentiment conditions?
- Do traders change their trading behavior during Fear and Greed markets?
- Which sentiment condition produces the highest profitability?
- How can historical sentiment be used to support better trading decisions?

---

# 🛠️ Tech Stack

## Programming Language

- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

## Development Environment

- Jupyter Notebook
- VS Code

## Version Control

- Git
- GitHub

---

# 📂 Dataset

The project combines two datasets.

## 1. Bitcoin Fear & Greed Index

Contains:

- Date
- Fear & Greed Score
- Market Sentiment Classification

---

## 2. Hyperliquid Historical Trading Data

Contains:

- Trader Account
- Cryptocurrency
- Execution Price
- Trade Size (USD)
- Trade Direction
- Position Details
- Closed Profit & Loss (PnL)
- Trading Fee
- Timestamp
- Transaction Information

---

# 📊 Project Workflow

```text
Data Collection
        │
        ▼
Data Inspection
        │
        ▼
Data Cleaning
        │
        ▼
Timestamp Standardization
        │
        ▼
Dataset Integration
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Visualization
        │
        ▼
Business Insights
        │
        ▼
Recommendations
```

---

# 📈 Key Performance Indicators (KPIs)

| KPI | Description |
|------|-------------|
| Average PnL | Average profit generated under each market sentiment |
| Win Rate | Percentage of profitable trades |
| Trade Frequency | Number of trades executed |
| Average Trade Size | Average trade size in USD |
| Position Category | Small, Medium and Large trades |
| Long vs Short Ratio | Distribution of Long and Short trades |
| Coin-wise Activity | Most actively traded cryptocurrencies |

---

# 📌 Key Findings

## 📍 Insight 1 — Highest Profitability

**Extreme Greed** market conditions produced the highest average trader profitability.

| Market Sentiment | Average PnL |
|------------------|------------:|
| Extreme Greed | **67.89** |
| Fear | 54.29 |
| Greed | 42.74 |
| Extreme Fear | 34.54 |
| Neutral | 34.31 |

---

## 📍 Insight 2 — Trading Activity

Trading activity was highest during **Fear** periods.

| Market Sentiment | Number of Trades |
|------------------|-----------------:|
| Fear | **61,837** |
| Greed | 50,303 |
| Extreme Greed | 39,992 |
| Neutral | 37,686 |
| Extreme Fear | 21,400 |

---

## 📍 Insight 3 — Win Rate

Trader win rate was highest during **Extreme Greed**.

| Market Sentiment | Win Rate |
|------------------|----------:|
| Extreme Greed | **46.49%** |
| Fear | 42.08% |
| Neutral | 39.70% |
| Greed | 38.48% |
| Extreme Fear | 37.06% |

---

# 📊 Visualizations

The project includes visualizations for:

- Market Sentiment Distribution
- Average Profit by Market Sentiment
- Win Rate Analysis
- Trade Size Distribution
- Long vs Short Distribution
- Most Traded Cryptocurrencies
- Profit vs Loss Comparison
- Daily Trading Activity
- Correlation Heatmap
- Position Category Distribution

---

# 💡 Business Recommendations

Based on the analysis:

- Incorporate market sentiment as an additional trading signal before entering positions.
- Reduce risk exposure during Extreme Fear due to historically lower profitability.
- Increase position sizing cautiously during historically favorable market conditions.
- Monitor changes in trading activity across sentiment cycles to improve decision-making.
- Combine sentiment indicators with technical analysis for stronger trading strategies.

---

# 📁 Repository Structure

```text
Cryptocurrency-Trader-Behavior-Analysis/

│
├── data/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── notebooks/
│   └── Trader_Performance_vs_Market_Sentiment_Analysis.ipynb
│
├── images/
│
├── outputs/
│
├── README.md
│
├── Project_Report.md
│
├── requirements.txt
│
└── .gitignore
```

---

# 🎯 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Business Insight Generation
- Python Programming
- Git & GitHub

---

# 🚀 Future Improvements

- Develop a Machine Learning model for profitability prediction.
- Build an interactive dashboard using Streamlit or Power BI.
- Automate the complete data analysis pipeline.
- Perform trader segmentation using clustering techniques.
- Extend the analysis using additional cryptocurrency market indicators.

---

# 📚 Dataset Acknowledgement

The datasets used in this project were sourced from a publicly shared analytics case study released by **Primetrade.ai**.

All data cleaning, preprocessing, feature engineering, exploratory data analysis, visualizations, and business recommendations presented in this repository were independently implemented by the author.

---

# ▶️ Getting Started

## Clone the repository

```bash
git clone https://github.com/ShouryaSrivastav/Cryptocurrency-Trader-Behavior-Analysis.git
```

## Navigate to the project

```bash
cd Cryptocurrency-Trader-Behavior-Analysis
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 👨‍💻 Author

**Shourya Srivastav**

Aspiring Data Analyst

### Skills

Python • SQL • Power BI • Excel • Statistics • Data Visualization

GitHub: https://github.com/ShouryaSrivastav

---

# 📄 License

This project is intended for educational and portfolio purposes only.