# Simple Moving Average with ATR and RSI
This project implements a trading strategy using a combination of Simple Moving Average (SMA), Average True Range (ATR), and Relative Strength Index (RSI). The strategy generates buy and sell signals based on the crossover of short-term and long-term SMAs, ATR for stop-loss levels, and RSI for additional confirmation.

## Overview
Moving Averages: The strategy uses short-term and long-term SMAs to identify trends in the price data.

Average True Range (ATR): ATR is employed to calculate stop-loss levels dynamically based on the volatility of the market.

Relative Strength Index (RSI): RSI is utilized to provide additional confirmation of overbought or oversold conditions in the market.

### Getting Started
## Prerequisites
- Python 3.x
- `yfinance` library
- `pandas` library
- `matplotlib.pyplot` library
- `numpy` library

- Install the required libraries using:

```bash
pip install yfinance pandas matplotlib numpy
```

Strategy Details
Buy Signal: Generated when the short-term SMA crosses above the long-term SMA, and RSI is below the overbought level.

Sell Signal: Generated when the short-term SMA crosses below the long-term SMA, and RSI is above the oversold level.

Stop-loss: Calculated dynamically using ATR.

Contributing
Feel free to contribute to the project by opening issues or submitting pull requests. Your feedback and contributions are highly appreciated.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Technical Analysis Library in Python
