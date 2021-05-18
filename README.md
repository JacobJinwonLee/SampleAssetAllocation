# SampleAssetAllocation

These are backtesting codes for asset allocation strategies.

## List of Asset Allocation Strategy (Static)
### Warning: In some cases, I used monthly return data in each backtest, when the values such as volatility and sharpe ratio calculated by the quantstat library were not converted on an annual basis. So it can be temporarily divided into sqrt(252/12) to convert it on an annual basis.

- R (A backtest with R, rmd file code and html file report)
- 60/40
- Core Four
- Four Funds
- Three Funds
- Harry Browne's Permanent Portfolio
- Tyler's Golden Butterfly
- Ray Dalio's All Seasons
- Yale (David Swensen) Portfolio
- Endowment Index by ETF

## List of Asset Allocation Strategy (Tactical)

- DAA (Defensive Asset Allocation)
- Modified DAA (modify asset group to be invested)

## Special (with leverage, option, futures, ...)

- BuyWrite (Covered Call - QYLD ETF)
- NTSX (Leveraged 60:40 ETF)
- SWAN (Black Swan ETF)
- PHDG (Invesco S&P 500 Downside Hedged ETF)
- DRSK (Aptus Defined Risk ETF)
