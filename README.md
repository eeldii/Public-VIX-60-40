# VIX-60-40
The 60/40 portfolio (60% stocks and 40% bonds) has long been a familiar allocation for investors seeking a balance between growth and stability. This project explores a different approach: can VIX-based allocation changes improve risk-adjusted results?

The backtester compares a fixed 60/40 portfolio with three strategies that adjust stock and bond allocations based on daily VIX readings: a tiered 60/40–70/30–80/20 strategy, a 60/40–80/20 strategy, and a 60/40–70/30 strategy. A strategy returns to 60/40 after VIX stays below 25 for a full month. Daily VIX signals set allocations for the following month; portfolio returns are calculated monthly.

The backtest spans January 2000 through September 2026. SPY adjusted closes represent S&P 500 returns. Bond returns use Vanguard’s U.S. Aggregate bond fund through November 2017, then an iShares fund tracking the Bloomberg Global Aggregate Bond Index from December 2017 onward. Because the earlier bond proxy is U.S.-only, results before December 2017 do not represent a pure global bond allocation. The app reports CAGR, Sharpe ratio, drawdown, two-year comparisons, reallocations, and time spent in each allocation.
