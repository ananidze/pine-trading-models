# 📈 Pine Script Trading Models

This project contains custom TradingView indicators built with Pine Script v6. They are designed to help you spot key market structures like sessions, liquidity, and order blocks.

## 🚀 How to Use These Scripts

1. Open [TradingView](https://www.tradingview.com/).
2. Open any chart.
3. At the bottom of the screen, click on the **Pine Editor** tab.
4. Copy the code from the `.pine` files in this folder and paste it into the Pine Editor.
5. Click **Add to Chart** in the top right corner of the Pine Editor.

---

## 📂 Included Indicators

### 1. Sessions & Order Blocks (`sessions-ob.pine`)
This is an all-in-one indicator that helps you see where the market is trading during different times of the day (like London or New York sessions) and spots "Order Blocks" where big players might be buying or selling.

**What it does:**
- Highlights the **Asian, London, and New York** sessions so you know when volume is highest.
- Automatically draws **Bullish (Buy) and Bearish (Sell) Order Blocks** on your chart.
- Filters out "weak" order blocks, only showing you the ones that had strong movement (displacement) behind them.

**Simple Trade Example:**
- *Wait for the London session to open.*
- *Look for the price to drop into a green (Bullish) Order Block.*
- *If you see a strong rejection, that could be a great place to buy!*

### 2. Liquidity Model (`liquidity-model.pine`)
This indicator focuses on "Liquidity"—the areas where lots of stop losses are resting. The market often acts like a magnet to these areas before reversing.

**What it does:**
- Finds **Liquidity Pools** (old highs and lows where stop losses are clustered).
- Detects **Liquidity Sweeps** (when the price pokes into a liquidity pool and immediately rejects).
- Keeps track of the market trend to ensure you're trading in the right direction.

**Simple Trade Example:**
- *The indicator marks an old "Equal Highs" liquidity pool above the current price.*
- *Price spikes up, breaks the high, but closes back down immediately (a sweep).*
- *This tells you buyers are trapped, making it a potential setup to sell short.*

---