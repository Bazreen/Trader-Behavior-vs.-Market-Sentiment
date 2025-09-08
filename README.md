# Trader-Behavior-vs.-Market-Sentiment
Data Science project analyzing trader performance vs Bitcoin Fear &amp; Greed Index
# Trader Behavior vs. Market Sentiment (Fear & Greed)

## 📌 Overview
This project explores the relationship between **trader performance** and **Bitcoin market sentiment** (Fear vs. Greed).  
The task was given as part of a **Junior Data Scientist hiring challenge**.

We analyze historical trading data from Hyperliquid and combine it with the **Fear & Greed Index** to uncover hidden patterns that can drive smarter trading strategies.

---

## 📂 Datasets
1. **historical_data.csv**  
   - Includes account, coin, execution price, side, size, closed PnL, etc.  

2. **fear_greed_index.csv**  
   - Includes date and market sentiment classification (Fear, Greed, Neutral).  

3. **merged_trades_with_sentiment.csv**  
   - Final dataset after merging both on `date`.

---

## ⚙️ Steps Performed
1. Data loading & cleaning  
2. Date parsing & dataset merging  
3. Exploratory Data Analysis (EDA)  
   - PnL distribution  
   - Number of trades  
   - Average PnL by sentiment  
4. Performance metrics  
   - Win rate by sentiment  
   - Daily PnL trends  
   - Account-level performance  
   - Coin-level performance  
5. Insights & conclusions

---

## 📊 Key Insights
- Traders’ **average PnL** and **win rates** vary significantly between **Fear** and **Greed** markets.  
- **Position sizes** and trading risk are higher in Greed phases.  
- Certain **accounts** and **coins** perform consistently better under specific sentiment regimes.  
- Market sentiment can be leveraged to **adapt trading strategies** for better outcomes.  

---

## 🚀 How to Run
1. Place all CSV files and the notebook in the same folder.  
2. Open the notebook in Jupyter Notebook / JupyterLab.  
3. Run all cells sequentially.  

---

## 📎 Deliverables
- [Jupyter Notebook](Trader_Behavior_vs_FearGreed_Analysis.ipynb)  
- [Merged Dataset](merged_trades_with_sentiment.csv)  
- [Quick Report](Trader_Behavior_vs_FearGreed_Report.html)  

---

## ✉️ Submission
Prepared by **Bazreen Bagali**  
- GitHub: *[Your GitHub Link]*  
- LinkedIn: *[Your LinkedIn Link]*  
