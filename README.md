# 📈 Stock Price Analyser

A simple Python project that shows live stock details and draws a price graph with **7-day** and **30-day moving averages**. Just type a stock symbol and the program does the rest, using real data from Yahoo Finance.

## ✨ Features

- Shows the company name and current price
- Shows today's change and change % compared to the previous close
- Downloads daily price history for any dates you choose
- Calculates 7-day and 30-day moving averages
- Draws a clear graph of the daily price and both averages
- Runs in a loop, so you can check many stocks. Type `QUIT` to exit
- Handles wrong symbols and network errors without crashing

## 🛠️ Built With

| Library | Use |
|---------|-----|
| `yfinance` | Gets stock data from Yahoo Finance |
| `pandas` | Stores data and calculates moving averages |
| `matplotlib` | Draws the graph |
| `numpy`, `seaborn` | Imported for future improvements |

## 🚀 How to Run

1. Install Python 3 and Jupyter Notebook.
2. Install the libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn yfinance
   ```
3. Open the notebook and run both cells.
4. Enter a stock symbol when asked, for example:
   - `RELIANCE.NS` (NSE, India)
   - `TCS.BO` (BSE, India)
   - `AAPL` (USA)
5. Enter a start date and an end date in `yyyy-mm-dd` format.
6. Type `QUIT` to stop the program.

## 🖥️ Sample Output

```
==========Complete Stock Analyser==========
 ==================================
 Company Name: Reliance Industries Limited
 Current Price: 1337.1 INR
 Change: 12.70 0.96%
 ===================================
```

Then a graph appears showing the daily price, the 7-day MA and the 30-day MA.

## 📊 What is a Moving Average?

It is the average of the last few days' prices. The 7-day MA reacts quickly (short-term trend) and the 30-day MA moves slowly (long-term trend). Together they help you see whether a price is going up, down or sideways.

## 🔮 Future Ideas

- Volume bars and candlestick charts
- More indicators (RSI, Bollinger Bands)
- Compare two or more companies
- Save data to CSV or Excel
- Simple app using Tkinter or Streamlit

## ⚠️ Disclaimer

This project is for learning only. It is **not** investment advice.
