# Trader Behavior vs Bitcoin Market Sentiment

## Overview
This project analyzes the relationship between Bitcoin market sentiment
(Fear vs Greed) and trader behavior using historical trading data from
Hyperliquid and the Bitcoin Fear & Greed Index.

The goal is to understand how market psychology impacts trader
profitability, risk exposure, and trade sizing, and to derive insights
that can inform smarter, sentiment-aware trading strategies.

---

## Datasets Used

### 1. Historical Trader Data (Hyperliquid)
Contains trade-level information including:
- Trade timestamps
- Profit and loss (Closed PnL)
- Position exposure (Start Position)
- Trade size (USD)
- Trade direction and execution details

### 2. Bitcoin Fear & Greed Index
Provides daily market sentiment classifications:
- Fear
- Greed

Each trade is mapped to the corresponding market sentiment based on date.

---

## Key Analysis Performed

- Data cleaning and preprocessing
- Timestamp standardization and date alignment
- Feature engineering for profitability and risk metrics
- Merging trader data with market sentiment
- Performance comparison (PnL and win rate) across sentiments
- Risk behavior analysis using position exposure and trade size
- Analysis of extreme gains and losses
- Visualization of sentiment-driven trading patterns

---

## Key Insights

- Traders tend to take higher risk during Greed market conditions.
- Greed periods show higher potential profits but also more extreme losses.
- Fear markets demonstrate more disciplined risk-taking and relatively
  consistent performance.
- Increased risk exposure does not always lead to better outcomes,
  particularly during Greed phases.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## How to Run
1. Clone the repository
2. Open the notebook in Google Colab or Jupyter Notebook
3. Run all cells sequentially

---

## Conclusion
Market sentiment plays a significant role in shaping trader behavior.
Incorporating sentiment-aware risk controls and position sizing strategies
can help traders and platforms improve long-term performance while
reducing downside risk.
