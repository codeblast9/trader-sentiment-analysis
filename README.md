# 🧠 Trader Performance vs Market Sentiment

This project analyzes the relationship between market sentiment (Fear/Greed) and trader performance using historical trade execution data and Bitcoin market sentiment indices.

## 📌 Objective
To identify patterns in trading behavior, PnL, and leverage across different market sentiment conditions — and deliver insights for smarter trading strategies.

## 📂 Datasets Used
The datasets used in this project are too large to be uploaded to GitHub. You can download them manually from the links below and place them in the same directory as the notebook:

🧾 Historical Trader Data (Hyperliquid):
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

📉 Bitcoin Fear & Greed Index:
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

Once downloaded, make sure the file names match those referenced in the Jupyter notebook.


## 🧪 Analysis Workflow
1. Clean and parse timestamp data
2. Extract and standardize date columns
3. Merge sentiment and trade records
4. Analyze PnL, leverage, and trade volume per sentiment
5. Identify top traders per sentiment
6. Time-series plots and comparative charts

## 📊 Key Insights
- Greed days have higher PnL and leverage, indicating more aggressive trading
- Fear days show higher PnL volatility and reduced trade activity
- Top traders can sustain profits even during Fear — possible resilient strategies

## 📁 Files
- trader_sentiment_analysis_SUBMIT_READY.ipynb – Full code and analysis
- merged_cleaned_data.csv – Final cleaned dataset (optional)
- README.md – Project summary and instructions

## ✅ How to Run
1. Clone the repo
2. Install dependencies via requirements.txt
3. Run trader_sentiment_analysis_SUBMIT_READY.ipynb

## 👤 Author
Priyanshu Jadhav – June 2025
