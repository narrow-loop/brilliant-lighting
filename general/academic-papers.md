Here’s a curated selection of **academic and working papers** on trading strategies—many considered profitable or influential within research and practitioner communities. I’ve focused on studies showing **realistic profitability** rather than purely theoretical or debunked approaches:

---

### Reinforcement Learning & AI‑Driven Strategies

* **Deep Reinforcement Learning for Trading** (Zhang, Zohren & Roberts, 2019)
  Applies DRL to continuous futures contracts across asset classes. Finds the method outperforms traditional momentum strategies even after transaction costs ([arXiv][1]).

* **A Deep Deterministic Policy Gradient-based Strategy for Portfolio Management** (Zhang, Jiang & Su, 2021)
  Uses DDPG with LSTM to manage a portfolio of U.S. stocks. Achieves 14.12% annual return and a Sharpe ratio \~0.599, \~33% higher than benchmarks ([arXiv][2]).

* **An Application of Deep Reinforcement Learning to Algorithmic Trading** (Théate & Ernst, 2020)
  Introduces the "Trading DQN" aimed at maximizing Sharpe ratio via artificial trajectory training. Reports promising DRL-based strategy performance ([arXiv][3]).

---

### Simplicity vs. Complexity in AI-Based Trading

* **Methods Matter: A Trading Agent with No Intelligence Routinely Outperforms AI‑Based Traders** (Cliff & Rollins, 2020)
  Demonstrates that very simple "sub‑zero‑intelligence" strategies can outperform public AI/ML trading algorithms when tested rigorously ([arXiv][4]).

---

### Technical Patterns & Emerging Markets

* **Profitable Candlestick Trading Strategies—The Evidence from a New Perspective** (Lu, Shiu & Liu, 2012)
  Tests two-day candlestick patterns on Taiwan’s Top 50 stocks (2002–2008). Finds three bullish reversal patterns yield profitable results (validated with out-of-sample tests and bootstrapping) ([IDEAS/RePEc][5]).

* **Profitable Trading Strategies Based on Price Multiples: Evidence from India** (Sehgal & Pandey, 2014)
  In BSE500 firms (2001–2013), portfolios of low P/E, P/B, and P/S stocks outperform higher multiples, especially low P/B stocks (≈2.4% monthly returns, risk-adjusted) ([ResearchGate][6]).

---

### Momentum and Investor-Friendly Strategies

* **Profitable Momentum Trading Strategies for Individual Investors** (Foltice & Langer, 2015)
  Investigates simplified momentum strategies accessible to retail investors (1991–2010 NYSE data). Finds net outperformance after realistic costs, with best trading frequency ranging from biannual to monthly depending on portfolio size ([IDEAS/RePEc][7]).

---

### Behavioral & Emerging Market Studies on Technical Analysis

* **Review of Technical Trading Rules in Southeast Asian Markets**
  Many studies find technical rules profitable in emerging markets (e.g., Taiwan, Malaysia, Thailand), though transaction costs can erode gains ([PMC][8], [SpringerOpen][9]).

* **Intraday Reversals vs. Momentum**
  In German Blue‑Chip stocks using 5‑minute returns, strong short‑term reversals observed among prior losers, while momentum strategies are largely unprofitable ([ResearchGate][10]).

---

### Practitioner‑Led Academic‑Style Research (Working Papers)

* **Andrew Aziz & Carlo Zarattini’s SSRN Working Papers** (2023–2025)
  A series of studies analyzing day‑trading strategies:

  * **Opening Range Breakout (ORB)** on leveraged ETFs (e.g., TQQQ): Annualized alpha >30% over multi-year periods.
  * **VWAP strategies**: Claimed returns over 8,000% on leveraged products with low drawdowns.
  * **Intraday momentum on SPY**: Cumulative return \~2,000%, Sharpe >1.3.
  * **Stocks-in‑Play** strategies: Net performance >1,600%, Sharpe \~2.8.
    These suggest disciplined, rule‑based strategies on liquid instruments can yield substantial profits ([維基百科][11]).

---

### Summary Table

| Strategy Type                         | Key Findings & Notables                                                              |
| ------------------------------------- | ------------------------------------------------------------------------------------ |
| **Reinforcement Learning (DRL/DDPG)** | Promising returns vs. benchmarks in futures & equity markets.                        |
| **Simple vs. AI-based**               | Surprisingly, ultra-simple strategies can outperform complex AI agents.              |
| **Candlestick & Technical Patterns**  | Profitable in certain markets (e.g., Taiwan), validated via out-of-sample tests.     |
| **Value/Momentum Strategies**         | Low valuation multiple stocks outperform; momentum works for retail with caution.    |
| **Emerging Market & Behavioral**      | Technical rules perform better in emerging markets; intraday reversals prevail.      |
| **Working Papers (Practitioner)**     | Day-trading setups (ORB, VWAP, momentum on SPY, Stocks-in-Play) show strong profits. |

---

### Community & Practitioner Sentiments

On platforms like Reddit, sentiment echoes academic findings:

> “Technical analysis has been widely used … about 30% to 40% of practitioners appear to believe that technical analysis is an important factor … at shorter time horizons to 6 months.”
> “Head-and-shoulders rule … returns … 13% and 19% per year for the mark and yen … moving average rules and momentum rules … outperformed the head-and-shoulders rules.” ([Reddit][12])

---

**Final Thoughts:** Many of these strategies show **theoretical or backtested profitability**, but real-world implementation requires accounting for **transaction costs, slippage, robustness, and overfitting**. Some findings (e.g., simple AI outperformers) serve as cautionary tales that performance claims must be rigorously vetted.

Let me know if you'd like deeper insights into any specific paper, methodology, or how they compare under different market conditions!

[1]: https://arxiv.org/abs/1911.10107?utm_source=chatgpt.com "Deep Reinforcement Learning for Trading"
[2]: https://arxiv.org/abs/2103.11455?utm_source=chatgpt.com "A Deep Deterministic Policy Gradient-based Strategy for Stocks Portfolio Management"
[3]: https://arxiv.org/abs/2004.06627?utm_source=chatgpt.com "An Application of Deep Reinforcement Learning to Algorithmic Trading"
[4]: https://arxiv.org/abs/2011.14346?utm_source=chatgpt.com "Methods Matter: A Trading Agent with No Intelligence Routinely Outperforms AI-Based Traders"
[5]: https://ideas.repec.org/a/eee/revfin/v21y2012i2p63-68.html?utm_source=chatgpt.com "Profitable candlestick trading strategies—The evidence from a new perspective"
[6]: https://www.researchgate.net/publication/273286777_Profitable_trading_strategies_based_on_price_multiple_information_Evidence_from_India?utm_source=chatgpt.com "(PDF) Profitable trading strategies based on price multiple information: Evidence from India"
[7]: https://ideas.repec.org/a/kap/fmktpm/v29y2015i2p85-113.html?utm_source=chatgpt.com "Profitable momentum trading strategies for individual investors"
[8]: https://pmc.ncbi.nlm.nih.gov/articles/PMC4583561/?utm_source=chatgpt.com "Performance of technical trading rules: evidence from Southeast Asian stock markets - PMC"
[9]: https://jfin-swufe.springeropen.com/articles/10.1186/s40854-022-00358-1?utm_source=chatgpt.com "Can investors profit by utilizing technical trading strategies? Evidence from the Korean and Chinese stock markets | Financial Innovation | Full Text"
[10]: https://www.researchgate.net/publication/330015961_Trading_Strategies_in_Intraday-Trading_Do_Momentum_and_Reversal_in_Stock_Prices_Exist?utm_source=chatgpt.com "(PDF) Trading Strategies in Intraday-Trading: Do Momentum and Reversal in Stock Prices Exist?"
[11]: https://en.wikipedia.org/wiki/Andrew_Aziz?utm_source=chatgpt.com "Andrew Aziz"
[12]: https://www.reddit.com/r/CryptoCurrency/comments/ovckm6?utm_source=chatgpt.com "The Profitability of Technical Analysis: A Review [Research paper]"
