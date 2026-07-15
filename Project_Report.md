# 📊 Project Report

# Cryptocurrency Trader Performance Analysis Using Bitcoin Market Sentiment

---

# Executive Summary

This project investigates the relationship between **Bitcoin market sentiment** and **cryptocurrency trader performance** by combining the **Bitcoin Fear & Greed Index** with **historical Hyperliquid trading data**.

The objective was to determine whether market sentiment influences trader profitability, trading activity, and overall trading behavior.

Using Python, the project follows a complete data analytics workflow including data collection, preprocessing, feature engineering, exploratory data analysis (EDA), visualization, and business insight generation.

---

# Business Problem

Financial markets are significantly influenced by investor psychology.

Periods of **Fear** and **Greed** often lead to changes in trader behavior, risk tolerance, and market participation.

The primary objective of this project was to answer the following questions:

- Does market sentiment affect trader profitability?
- Does trader activity change under different market conditions?
- Which sentiment conditions produce better trading performance?
- Can historical sentiment be used to support trading decisions?

---

# Project Objectives

The project aimed to:

- Analyze historical cryptocurrency trading behavior.
- Integrate market sentiment with trading data.
- Measure trader performance under different sentiment conditions.
- Generate actionable business insights.
- Recommend data-driven trading strategies.

---

# Dataset Description

Two independent datasets were used.

## Dataset 1: Bitcoin Fear & Greed Index

The dataset contains daily Bitcoin market sentiment information.

### Features

- Date
- Fear & Greed Value
- Market Sentiment Classification

---

## Dataset 2: Hyperliquid Historical Trading Data

The dataset contains historical cryptocurrency trading records.

### Features

- Trader Account
- Coin
- Execution Price
- Trade Size (USD)
- Trade Size (Tokens)
- Trade Direction
- Position Information
- Closed Profit & Loss (PnL)
- Trading Fee
- Timestamp
- Transaction Details

---

# Data Preparation

The following preprocessing steps were performed before analysis.

## 1. Data Inspection

- Loaded both datasets using Pandas.
- Examined dataset structure.
- Reviewed data types.
- Identified missing values.
- Checked duplicate records.

---

## 2. Data Cleaning

Performed:

- Missing value verification
- Duplicate verification
- Datetime conversion
- Column formatting

---

## 3. Timestamp Standardization

Trading timestamps were converted into daily dates to match the frequency of the Fear & Greed Index.

This ensured both datasets could be accurately integrated.

---

## 4. Dataset Integration

The datasets were merged using the **Date** column.

This allowed each trade to inherit the corresponding market sentiment for that trading day.

---

## 5. Feature Engineering

Additional analytical features were created.

Examples include:

- Position Category
- Daily Trade Count
- Average Trade Size
- Win/Loss Indicator
- Long vs Short Distribution

These derived features enabled deeper behavioral analysis.

---

# Exploratory Data Analysis (EDA)

Several analyses were performed to understand trader behavior.

## Analysis Performed

- Market Sentiment Distribution
- Average Profit by Sentiment
- Win Rate Analysis
- Trade Frequency Analysis
- Position Size Distribution
- Long vs Short Analysis
- Coin-wise Trading Activity
- Profit vs Loss Comparison
- Daily Trading Activity
- Correlation Analysis

---

# Key Performance Indicators (KPIs)

The following KPIs were evaluated.

| KPI | Purpose |
|------|---------|
| Average Closed PnL | Measure trader profitability |
| Win Rate | Percentage of profitable trades |
| Trade Frequency | Trading activity level |
| Average Trade Size | Capital deployed per trade |
| Position Category | Trading behavior analysis |
| Long vs Short Ratio | Position preference |
| Coin-wise Distribution | Asset popularity |

---

# Key Findings

## Finding 1: Highest Profitability During Extreme Greed

Average profitability increased significantly during **Extreme Greed**.

| Market Sentiment | Average PnL |
|------------------|------------:|
| Extreme Greed | **67.89** |
| Fear | 54.29 |
| Greed | 42.74 |
| Extreme Fear | 34.54 |
| Neutral | 34.31 |

**Interpretation**

Bullish market conditions historically provided better profit opportunities for traders.

---

## Finding 2: Fear Generated the Highest Trading Activity

| Market Sentiment | Number of Trades |
|------------------|-----------------:|
| Fear | **61,837** |
| Greed | 50,303 |
| Extreme Greed | 39,992 |
| Neutral | 37,686 |
| Extreme Fear | 21,400 |

**Interpretation**

Periods of uncertainty encouraged greater market participation and higher trading volumes.

---

## Finding 3: Highest Win Rate During Extreme Greed

| Market Sentiment | Win Rate |
|------------------|----------:|
| Extreme Greed | **46.49%** |
| Fear | 42.08% |
| Neutral | 39.70% |
| Greed | 38.48% |
| Extreme Fear | 37.06% |

**Interpretation**

Trader success rates improved considerably during bullish market conditions.

---

# Business Insights

The analysis suggests that market sentiment has a measurable relationship with trader performance.

Major observations include:

- Positive sentiment generally corresponded with higher profitability.
- Fear periods resulted in the highest trading activity.
- Trader win rates improved under bullish conditions.
- Trading behavior varied across different sentiment categories.

---

# Business Recommendations

Based on the analysis, the following recommendations are proposed.

### Recommendation 1

Incorporate market sentiment as an additional trading signal before entering positions.

---

### Recommendation 2

Reduce risk exposure during **Extreme Fear** because profitability and win rates decline.

---

### Recommendation 3

Increase position sizes cautiously during historically profitable market conditions while maintaining disciplined risk management.

---

### Recommendation 4

Monitor shifts in market sentiment to optimize trading strategies and improve decision-making.

---

# Limitations

The project has several limitations.

- Analysis is based on historical data.
- External macroeconomic factors were not included.
- Market sentiment was represented only by the Bitcoin Fear & Greed Index.
- Results should not be interpreted as financial advice.

---

# Future Scope

Potential improvements include:

- Machine Learning models for profitability prediction.
- Time-series forecasting.
- Trader segmentation using clustering.
- Real-time sentiment analysis.
- Interactive dashboard development using Streamlit or Power BI.
- Automated ETL pipeline.

---

# Skills Demonstrated

This project demonstrates practical experience in:

- Python Programming
- Pandas
- NumPy
- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Business Insight Generation
- Git
- GitHub

---

# Conclusion

This project demonstrates how integrating **market sentiment** with **historical trading data** can provide valuable insights into cryptocurrency trader behavior.

The findings indicate that trader profitability, trading frequency, and win rates vary across different market sentiment conditions. By combining sentiment indicators with historical trading metrics, analysts can better understand market behavior and support more informed, data-driven decision-making.

---

# Dataset Acknowledgement

The datasets used in this project were sourced from a publicly shared analytics case study released by **Primetrade.ai**.

All data cleaning, preprocessing, feature engineering, exploratory data analysis, visualizations, and business recommendations presented in this report were independently implemented by the author.

---

# Author

**Shourya Srivastav**

Aspiring Data Analyst

Skills: Python | SQL | Power BI | Excel | Statistics | Data Visualization