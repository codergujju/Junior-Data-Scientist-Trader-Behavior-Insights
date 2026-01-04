# Junior-Data-Scientist-Trader-Behavior-Insights

📊 Trader Behavior Insights: Market Sentiment Analysis
🧠 Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data from Hyperliquid. The goal is to uncover behavioral patterns that can inform smarter, sentiment-aware trading strategies in the Web3 ecosystem.

🎯 Objective

To understand how market sentiment impacts:

Trader profitability

Risk-taking behavior

Trade frequency and leverage usage

📂 Datasets Used
1️⃣ Bitcoin Fear & Greed Index

Columns:

timestamp

value

classification (Fear / Greed)

date

2️⃣ Hyperliquid Historical Trader Data

Columns include:

Account

Coin

Execution Price

Size (Tokens & USD)

Side

Timestamp / Timestamp IST

Closed PnL

Leverage

Fees

Trade ID

Transaction Hash

🔧 Methodology

Data Cleaning

Handled missing values and incorrect datatypes

Converted timestamps with mixed formats using dayfirst=True

Standardized date formats for merging

Feature Engineering

Encoded sentiment (Fear = 0, Greed = 1)

Extracted trade dates from timestamps

Merged trader data with sentiment data on date

Exploratory Data Analysis (EDA)

Analyzed Closed PnL distribution by sentiment

Compared trade frequency and leverage usage

Evaluated volatility across Fear vs Greed phases

📈 Key Insights

📌 Trades executed during Greed periods show higher average profitability but greater volatility

📌 Fear periods result in lower but more stable returns

📌 Traders tend to use higher leverage during Greed, amplifying both profits and losses

📌 Market sentiment strongly influences trader risk behavior

💡 Business Impact

These insights can help:

Design sentiment-aware trading strategies

Improve risk management frameworks

Adjust leverage exposure dynamically

Enhance trader behavior modeling in Web3 platforms

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook

📄 Project Files

Main_file.ipynb → Full analysis & code

merged_trader_sentiment_data.csv → Final merged dataset

Trader_Behavior_Insights_Professional_Report_LargeFont.pdf → One-page analytical report
