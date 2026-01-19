\# **Risk-Managed Equity Strategies on SPY**



\## **Project Overview**

This project compares different risk-managed investment strategies applied to the SPY ETF over a 20-year horizon.



The goal is to evaluate whether simple risk management techniques

(trend and volatility scaling) can improve the risk-adjusted performance

of a traditional buy-and-hold strategy.



\## **Data**

\- Asset: SPY ETF

\- Frequency: Daily

\- Time horizon: 20 years

\- Data source: Yahoo Finance



\## **Strategies Implemented**

1\. Buy \& Hold

2\. Trend Strength Scaling (SMA-based)

3\. Volatility Targeting

4\. Trend + Volatility Combined



All strategies remain fully invested, adjusting exposure dynamically.



\## **Performance Metrics**

\- CAGR

\- Annualized Volatility

\- Sharpe Ratio

\- Maximum Drawdown



\## **Conclusions**

This study compares Buy \& Hold with three risk-managed strategies applied to the S\&P 500 ETF (SPY) over a 20-year horizon.**

The strategies are evaluated in terms of return, risk, and downside protection.**



Buy \& Hold delivers the highest long-term return (CAGR ≈ 10.7%), but it also exhibits the highest volatility and the largest maximum drawdown (over −55%).**

This confirms that full market exposure maximizes growth but exposes the investor to severe drawdowns during market crises.**



SMA Strength reduces volatility and drawdowns relative to Buy \& Hold, but at the cost of a lower CAGR.**

Trend-based exposure smoothing improves risk control but does not fully compensate for lost upside.**



Volatility Targeting significantly lowers portfolio volatility and drawdown, achieving a much better risk-adjusted performance.**

Although absolute returns are reduced, the Sharpe ratio improves substantially, highlighting the effectiveness of volatility scaling as a risk management tool.**



Trend + Volatility delivers the best overall risk-adjusted performance.**

While it produces the lowest CAGR among the strategies, it achieves:**

	•	the lowest volatility,**

	•	the smallest maximum drawdown,**

	•	and the highest Sharpe ratio.**



This confirms that combining trend information with volatility control leads to a more stable and robust investment profile, at the cost of reduced absolute returns.**



Overall, the results highlight a clear trade-off between return maximization and risk control.**

Risk-managed strategies do not aim to outperform the market in terms of raw returns, but rather to deliver smoother equity curves and superior risk-adjusted performance.**



\## **Assumptions and Limitations**

\- No transaction costs or slippage

\- Results represent theoretical upper bounds

\- Backtest is not intended as investment advice



\## **Future works**

**Possible extensions : multi-asset, leverage constraints, regime detection.**





\## **How to Run**

```bash

python main.py

