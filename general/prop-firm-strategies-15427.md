Perfect 👍 Let’s design a **prop-firm-ready strategy** step by step.
I’ll make it practical, with **clear entry/exit rules, risk controls, and prop-firm constraints in mind (FTMO, MyForexFunds, etc.)**.

---

# 📊 Prop-Firm-Friendly Strategy: Trend-Pullback System

This is a **hybrid trend-following + pullback entry** strategy. It works well on **indices (US30, NAS100, DAX)** or **majors (EURUSD, GBPUSD, XAUUSD)** because of strong liquidity.

---

## 1. **Setup**

* **Timeframe:** 15m (FTMO-friendly, enough trades but not over-scalping)
* **Indicators:**

  * 50 EMA (trend direction)
  * 200 EMA (long-term filter)
  * ATR(14) (for stop-loss sizing)

---

## 2. **Rules**

### ✅ Entry

* **Trend Filter:** Only trade long if 50 EMA > 200 EMA, short if 50 EMA < 200 EMA.
* **Pullback Trigger:** Wait for price to touch (or slightly pierce) the 50 EMA.
* **Confirmation:** Enter if a rejection candle (pin bar / engulfing) forms at the EMA.

### ✅ Stop Loss

* Place SL **1.5 × ATR below entry (longs) / above entry (shorts)**.
* This keeps SL adaptive to volatility.

### ✅ Take Profit

* Base target = **2 × SL distance** (so Risk\:Reward = 1:2).
* Trail stop once trade reaches 1R (move SL to breakeven).

### ✅ Risk Management

* Risk **0.5% per trade** (allows multiple attempts without busting daily limit).
* Max **2 trades open simultaneously**.
* Stop trading if **daily drawdown reaches -2%** (FTMO rule buffer).

---

## 3. **Example Trade**

* US30 (Dow) on 15m:

  * 50 EMA > 200 EMA (uptrend).
  * Price retraces to 50 EMA.
  * Bullish engulfing candle appears → enter long.
  * ATR(14) = 60 points → SL = 90 points below.
  * TP = 180 points.
  * Risk 0.5% of equity → adjust lot size accordingly.

---

## 4. **Why This Works for Prop Firms**

* **No martingale / grid** (prop firms hate that).
* **Fixed risk per trade**, drawdown controlled.
* **High R\:R (1:2)** means even a 40% win rate passes.
* **Simple rules** → easy to stay disciplined under evaluation stress.
* **Adaptable to assets** (indices, gold, majors).

---

## 5. **Performance Expectation**

* **Win rate:** \~40–55%
* **Risk\:Reward:** 1:2
* **Expected monthly return:** 5–15% (enough to hit prop targets without over-leverage).
* **Max drawdown:** 5–8% if followed strictly.

---

👉 This is a **baseline system** — robust, simple, and FTMO-proof.
We can refine it further by adding:

* News filter (skip high-impact events unless trading news intentionally).
* Multi-timeframe confirmation (trend on 1H, entry on 15m).
* Position scaling (add partial positions on re-tests).

---

Do you want me to **code this into a backtest (Python/Backtrader)** so we can check performance metrics (PnL curve, drawdown, win rate), or do you prefer a **manual trading plan template** you could apply right away?
