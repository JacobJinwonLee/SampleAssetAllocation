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
- New All Seasons (all seasons without nominal bond)
- All Seasons with Crypto (1%, 1.5%, 3%, 6% crypto)

## List of Asset Allocation Strategy (Tactical)

- Sector Rotation (with Dual Momentum)
- DAA (Defensive Asset Allocation)
- VAA (Vigilant Asset Allocation)
- Bond Momentum (High Yield, Convertible Bond, Inter-term Treasury Momentum)

## Special (with leverage, option, futures, ...) ETFs

- BuyWrite (Covered Call - QYLD ETF)
- NTSX (Leveraged 60:40 ETF)
- SWAN (Black Swan ETF)
- PHDG (Invesco S&P 500 Downside Hedged ETF)
- DRSK (Aptus Defined Risk ETF)
- TAIL (Cambria Tail Risk ETF)
- IVOL (Quadratic Interest Rate Volatility and Inflation Hedge ETF)
- HNDL (NASDAQ 7HANDL Index ETF)
