This Python-based tool analyzes stock market trends using historical price data. It downloads stock data, calculates technical indicators, and visualizes trends to identify potential bullish or bearish signals.

The script performs three main tasks:

* 1. Downloads historical stock price data.
- 2. Calculates trend indicators like Moving Averages and RSI.
- 3. Visualizes the data to interpret market trends.
- 
This tool is beneficial for learning financial data analysis and experimenting with algorithmic trading ideas.

Features:

* - Downloads historical stock price data.
- - Calculates:
-   - 50-day moving average
-   - 200-day moving average
-   - Relative Strength Index (RSI)
- - Detects simple trend signals (Bullish/Bearish).
- - Visualizes stock price trends using charts.

Requirements:

- Python 3.8 or higher.
* - Required libraries: yfinance, pandas, matplotlib.
- - Install dependencies using pip: pip install yfinance pandas matplotlib.

Project Structure:

- stock-trend-analyzer/
- trend_analyzer.py
- README.md

How It Works:

- The script downloads historical stock price data using Yahoo Finance.
- Two key indicators are calculated:
*   - Moving Averages (50-day and 200-day).
- - If the 50-day moving average crosses above the 200-day average, the trend is labeled Bullish.
- If it falls below, the trend is labeled Bearish.
- Relative Strength Index (RSI) measures momentum in price movements.
* - RSI > 70 indicates overbought conditions, while RSI < 30 indicates oversold conditions.

Running the Script:

- Run the script using: python trend_analyzer.py
You can modify the stock ticker in the script.
ticker = "AAPReplace “L” with any ticker symbol, for instance:

- TSLA
- MSFT
- NVDA
- SPY

Example Output:

The script prints the latest calculated indicators, including:

* - Closing price
- - Moving averages
- - RSI
- - Trend classification
- 
Additionally, it generates two charts:

1. - Stock price with moving averages
2. - RSI momentum chart

Possible Improvements:

Future enhancements could include:

* - Backtesting trading strategies
- - Automatically scanning multiple stocks
- - Adding more indicators (such as MACD and Bollinger Bands)
- - Building a dashboard using Plotly or Streamlit
- - Applying machine learning for price prediction

Disclaimer:

This project is intended for educational and research purposes only. It should not be used as financial advice or the sole basis for trading decisions.
