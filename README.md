# 📊 Trader Performance vs Market Sentiment Analysis

## 📌 Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and Hyperliquid trader performance.  
The goal is to understand how market emotions affect trader behavior, profitability, and trading decisions.

---

## 🎯 Objective
- Analyze trader performance during different market sentiment conditions  
- Study how Fear and Greed affect trading behavior  
- Identify trader patterns and segments  
- Create actionable trading insights  

---

## 📁 Datasets Used

### 1. Bitcoin Fear & Greed Index
- Date  
- Classification (Fear / Greed / Extreme Fear / Extreme Greed / Neutral)  
- Value  

### 2. Hyperliquid Trader Data
- Account  
- Coin  
- Execution Price  
- Size (Tokens & USD)  
- Side (Buy/Sell)  
- Closed PnL  
- Timestamp  
- Fees  
- Order details  

---

## 🛠 Tools & Libraries
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Google Colab  

---

## 🔄 Workflow

### 1. Data Preparation
- Loaded both datasets  
- Checked missing values and duplicates  
- Converted timestamps to date format  
- Merged datasets using date  

### 2. Feature Engineering
Created key metrics:
- Daily PnL  
- Win Rate  
- Trade Count  
- Average Trade Size  
- Long vs Short Ratio  
- Trader segmentation  

### 3. Exploratory Data Analysis
- PnL vs Market Sentiment  
- Win Rate vs Sentiment  
- Trade behavior changes  
- Trader performance comparison  
- Segment analysis  

---

## 📊 Key Insights

- Traders performed better during **Extreme Greed** conditions  
- Trade size was higher during **Fear periods**  
- Trading activity changed with market sentiment  
- Different trader groups showed different profitability patterns  

---

## 💡 Strategy Recommendations

### Strategy 1
Reduce position size during **Fear / Extreme Fear** periods to manage risk.

### Strategy 2
Maintain controlled trading activity during **Greed periods** to take advantage of higher market participation.

---

## 📌 Note on Leverage
The dataset does not contain a leverage column, so leverage analysis was not possible. The analysis focuses on available metrics like PnL, trade size, win rate, and trading behavior.

---

## 📂 Repository Structure

```
Trader-Performance-vs-Market-Sentiment-Analysis/
│
├── README.md
├── Trader_Performance_vs_Market_Sentiment_Analysis.ipynb
├── fear_greed_index.csv
└── historical_trader_data.csv
```

---

## 🚀 How to Run

1. Clone this repository  
2. Open the notebook in Google Colab or Jupyter Notebook  
3. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib
   ```
4. Run all cells sequentially  
5. View results and insights  

---

## 👨‍💻 Author

**Aditya Khanna**  
- GitHub: https://github.com/aditya-khanna2006  
- LinkedIn: https://www.linkedin.com/in/aditya-khanna2006  

---

## 📈 Results Summary
This project shows that market sentiment has a clear impact on trader behavior and performance. Traders adjust their risk and activity based on Fear and Greed conditions, which can be used for better trading strategies.
