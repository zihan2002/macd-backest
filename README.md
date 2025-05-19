# MACD
A simple MACD strategy with visual backtesting in python
## Strategy Overview
MACD is a momentum-based technical indicator that compares short-term and long-term moving averages.
- **Buy signal**: When the short-term MA crosses above the long-term MA
- **Sell signal**: When the short-term MA crosses below the long-term MA
The MACD Oscillator is defined as the difference between these two averages.
---
## Visualizations
- Price chart with buy/sell signals (green ▲ for buy, red ▼ for sell)
- MACD Oscillator bar chart
- Short-term vs long-term moving averages
---
### 1. Price Chart with Buy/Sell Signals

This chart displays the stock's closing price over time, with signal points overlaid:

- **Green ▲**: Buy signal – when the short-term moving average crosses **above** the long-term moving average
- **Red ▼**: Sell signal – when the short-term MA crosses **below** the long-term MA

These signals represent **entry** and **exit** points based on trend momentum.

From the chart can visually inspect:
- Whether the signals correctly capture **upward trends**
- Whether the strategy **exits before major reversals**

---
### 2. MACD Oscillator Bar Chart

The MACD oscillator is calculated as the difference between the short and long moving averages:

- **Above 0**: Indicates upward momentum
- **Below 0**: Indicates downward momentum

The histogram bars show the **strength of trend**. When the oscillator crosses 0, it often suggests a **potential turning point**.

---

### 3. Moving Averages Overlaid

This chart shows the short-term (blue) and long-term (orange) moving averages directly over the price series:

- The **crossovers** between these two lines are what generate buy/sell signals
- For example, when the blue line moves above the orange line → buy signal is generated
---
