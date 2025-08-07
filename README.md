# 📈 SentimentStockPredictor

A project that combines stock price trends with real-time news sentiment analysis using both classical and deep learning NLP methods to support smarter stock movement forecasting.

---

## 🚀 Project Overview

This tool extracts stock price data and financial news headlines, performs sentiment analysis, and merges them to create a dataset suitable for further analysis, forecasting, or visualization.

---

## 🧠 Features

- ✅ **Stock Data Fetching** (e.g., AAPL)
- 📰 **News Sentiment Analysis** via:
  - 🔹 VADER (rule-based sentiment analysis)
  - 🔹 FinBERT (BERT-based financial tone classifier)
- 🔗 **Merging Stock & Sentiment** data by date
- 📊 Ready for visualization/dashboard integration (Streamlit or Jupyter)
- 🧪 Extensible for ML or statistical modeling

---

## 📁 Folder Structure

```bash
SentimentStockPredictor/
├── dashboard/                  # (optional) for dashboard frontend
├── data/
│   ├── price_data/             # CSVs of historical stock data
│   └── sentiment_data/         # Raw and scored news data
├── src/
│   ├── fetch_stock.ipynb               # Loads stock data
│   ├── sentiment_analysis.ipynb        # VADER sentiment scoring
│   ├── finbert_sentiment_analysis.ipynb# FinBERT sentiment scoring
│   └── merge_sentiment_price.ipynb     # Merge and align data
└── README.md


---

## 🔧 How to Run

1. Open each notebook in order:
    - `fetch_stock.ipynb`
    - `sentiment_analysis.ipynb`
    - `finbert_sentiment_analysis.ipynb`
    - `merge_sentiment_price.ipynb`

2. Run all cells to generate your final dataset with merged sentiment scores and stock prices.

---

## 🙋 Author

**Khac Minh Dai Vo**  
GitHub: [@zincoi172](https://github.com/zincoi172)

