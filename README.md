# Data_Science_Task

📊 Trading Behavior vs Market Sentiment Analysis

🧠 Project Overview

This project analyzes how Bitcoin market sentiment (Fear & Greed Index) influences trader performance (PnL) using real trading data.

The objective is to uncover patterns and generate insights that can help design data-driven trading strategies.

## Instalation
📁 Project Structure

├── Data Science_Task.ipynb      # Main analysis notebook

├── fear_greed_index.csv        # Sentiment dataset

├── historical_data.csv         # Trading dataset

├── sentiment_analysis_output.csv (generated)

└── README.md

### Prerequisites

📊 Datasets

🔹 Fear & Greed Index
    Provides daily market sentiment

    Categories:

    Extreme Fear
    Fear
    Neutral
    Greed
    Extreme Greed

🔹 Historical Trader Data

    Contains executed trades with:

    Price
    Size
    Side (Buy/Sell)
    Timestamp
    Closed PnL
 
## ⚙️ Workflow
1️⃣ Data Preprocessing

    Converted timestamps to datetime
    Extracted daily trading activity

2️⃣ Data Aggregation
    Computed daily total PnL

3️⃣ Data Merging
    Joined trading data with sentiment data on date

4️⃣ Analysis
    Compared performance across sentiment categories

    Calculated:
    Average PnL
    Total PnL
    Trade frequency

5️⃣ Visualization

    Bar chart:
    Avg PnL vs Sentiment
    Histogram: PnL distribution

## 🛠️  Technologies
    Python 🐍
    Pandas
    Matplotlib
    Jupyter Notebook

## ⭐ If you found this useful
    Give the repo a star ⭐ and feel free to fork it!
 
