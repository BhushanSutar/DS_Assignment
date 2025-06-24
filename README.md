# DS_Assignment

# 🧠 Trader Behavior vs Market Sentiment Analysis

## 📌 Project Objective

This project explores the relationship between market sentiment (Fear vs Greed) and trader performance on the Hyperliquid platform. The goal is to uncover behavioral patterns that can inform smarter trading strategies by analyzing trade outcomes against sentiment shifts.



## 📊 Datasets Used

1. **Fear-Greed Index** (`fear_greed_index.csv`)  
   - Date-wise market sentiment: "Fear" or "Greed"

2. **Trader Data** (`historical_data.csv`)  
   - Trade-level data including price, size, side, PnL, and timestamp



## 📈 Key Analyses

- ✅ Merged sentiment with trade data by date
- ✅ Calculated metrics:
  - Average PnL by sentiment
  - Win rate (% profitable trades)
  - Average trade size
- ✅ Created visualizations (boxplots, bar charts)



## 📌 Key Insights

| Metric                 | Greed Days        | Fear Days         |
|------------------------|-------------------|--------------------|
| Avg. Profit (PnL)      | Higher             | Lower              |
| Win Rate               | Higher             | Lower              |
| Trade Size (USD)       | Larger trades      | Smaller trades     |

- Traders are more profitable and confident during **Greed**.
- Sentiment can guide **position sizing and risk management**.
- Incorporating sentiment into trading systems may improve performance.



## 📁 Deliverables

- ✅ `DS_Assignment.ipynb': Clean Colab notebook with full analysis
- ✅ Visualizations and summary
- ✅ Insights and implications


## 🤖 Predictive Modeling (Bonus)

To take the analysis a step further, a **Random Forest Classifier** was developed to predict whether a trade will be **profitable** based on features such as:

- Market Sentiment (Fear/Greed)  
- Trade Size (USD)  
- Execution Price  
- Coin/Symbol  
- Trade Side (Buy/Sell)

### 📦 Features Used
- `Sentiment`
- `Size USD`
- `Execution Price`
- `Coin`
- `Side`

### 💡 Strategic Value

- Can be used in **trading bots or dashboards** to assess trade potential
- Helps avoid **low-probability trades** during Fear sentiment
- Can **recommend optimal conditions** based on historical data



## 📫 Contact

Prepared by: *Bhushan Sutar*  
Email: *bhushansutar1904@gmail.com*  
Date: *24/06/25*  
For: Junior Data Scientist – Trader Behavior Insights Assignment  
