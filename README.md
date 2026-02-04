# -Trader-Behavior-Insights
# Fear vs Greed: Trader Behavior on Hyperliquid

## Project Goal
Analyze how Bitcoin market sentiment (Fear/Greed) affects trader behavior and performance on Hyperliquid.

## Files
- analysis.ipynb → full notebook
- charts.png → output charts

## How to Run
Open `analysis.ipynb` in Google Colab or Jupyter.
Upload:
- fear_greed_index.csv
- historical_data.csv
Run all cells.

## Methodology
- Cleaned datasets and aligned timestamps
- Merged sentiment with trades
- Created daily trader metrics (PnL, win rate, trades/day, size, direction)
- Segmented traders by frequency

## Key Insights
1. Traders earn more and win more during Fear days.
2. Traders overtrade (~4×) during Fear without increasing position size.
3. Frequent traders outperform infrequent traders, especially during Fear.

## Strategy Recommendations
- Limit trade frequency during Fear to avoid overtrading.
- Increase participation for frequent traders during Fear regimes.

