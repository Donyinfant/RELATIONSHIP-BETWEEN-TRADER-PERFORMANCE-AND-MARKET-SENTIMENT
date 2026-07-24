# RELATIONSHIP-BETWEEN-TRADER-PERFORMANCE-AND-MARKET-SENTIMENT
Trader performance vs. Bitcoin Fear &amp; Greed Index — analysis of 211K+ Hyperliquid trades

# Trader Performance vs. Market Sentiment
An analysis exploring the relationship between Bitcoin market sentiment (Fear & Greed Index) 
and trader performance on Hyperliquid. Merges 211,224 trade-level records from 32 accounts 
with daily sentiment classifications to uncover patterns in win rate, profitability, and 
positioning behavior across Extreme Fear, Fear, Neutral, Greed, and Extreme Greed regimes.

## Key Finding
Performance follows a U-shaped pattern rather than a linear trend — traders performed best 
during sentiment *extremes* (Fear and Extreme Greed), not in the calmer middle of the 
spectrum. This is statistically confirmed via Welch's t-test (Extreme Fear vs. Extreme 
Greed: p = 0.0008).

## Contents
- `analysis_script.py` — data merging, metrics, statistical tests, and report generation
- `RELATIONSHIP BETWEEN TRADER PERFORMANCE AND MARKET SENTIMENT.docx` — full write-up
- `avg_pnl_by_Emotion.png` — profitability-by-sentiment chart

## Data Sources
- Bitcoin Fear & Greed Index (daily sentiment classification)
- Hyperliquid historical trade data (execution price, size, side, closed PnL, etc.)

## Tools
Python, pandas, matplotlib, scipy, python-docx
