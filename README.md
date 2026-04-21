# Quantitative Time-Series Analysis: US Sector ETFs

Final Project for IC Quant Mentorship, Spring 2026

## Overview
Analysis of daily log returns for five US equity ETFs (SPY, XLK, XLF, XLE, XLV) from 205 through 2026, covering exploratory data analysis, correlation structure, and univariate ARIMA forecasting of SPY returns.

## Data
- **Source:** Yahoo Finance, pulled via `yfinance`
- **CSV:** `data/sector_prices.csv` (adjusted close prices, 2015-01-02 to 2026-04-17, 2839 trading days)

## Reproducing
```bash
pip install -r requirements.txt
juptyer lab analysis.ipynb