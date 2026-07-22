# Brent Crude Price Analysis

## Overview
A small project for the analysis and plotting of brent oil prices.
Tools used (Python, yfinance, pandas, matplotlib).

## Features
- Historical Brent Crude price data (via yfinance)
- Moving averages (20/50-day) for trend analysis
- Rolling volatility (30-day std dev of returns) - risk metric
- Return distribution histogram - shows fat tails / non-normal distribution
- Key geopolitical event overlay
- Rolling correlation with WTI crude

 ## Key Findings
- Daily returns show a fat-tailed distribution (extreme price moves occur more frequently than a normal distribution would predict), highlighting limitations of risk models like basic VaR that assume normality.
- Brent-WTI correlation typically sits at 0.85-0.95 but dips sharply during regional supply shocks (e.g. WTI's negative pricing event, April 2020), reflecting Cushing's landlocked storage constraints vs Brent's seaborne global pricing.
- Price chart overlaid with major geopolitical events (e.g. Russia-Ukraine invasion, Feb 2022) shows Brent's sensitivity to supply-side shocks.

## Tech Stack
Python, pandas, yfinance, matplotlib, Jupyter Notebook

## Setup
```bash
pip install yfinance pandas matplotlib
```
