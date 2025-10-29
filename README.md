# Trade Behavior Vs Market Sentiment Assignment By Shyam SR

This package contains analysis artifacts for the **Trader Behavior vs Market Sentiment** assignment.


## Key Deliverables
- `ds_report.pdf` — 5-page summary with regime charts.
- `notebook_1.ipynb` — Reproducible notebook.
- `csv_files/` — Derived metrics and cohorts.
- `outputs/` — Visuals (PNG).


## Structure
```
PrimeTradeAIBitCoinCryptoCurrencyJob/
├── notebook_1.ipynb
├── csv_files/
│   ├── daily_aggregates.csv
│   ├── daily_with_sentiment.csv
│   └── fear_greed_summary.csv
├── outputs/
│   ├── timeseries_total_pnl.png
│   ├── avg_daily_pnl_by_sentiment.png
│   ├── boxplot_daily_pnl_by_sentiment.png
│   
├── ds_report.pdf
└── README.md
```

## Notes
- All dates were aligned on daily granularity and merged with the Fear/Greed classification.
- Daily aggregates include: trades, accounts, symbols, total_pnl, win_rate, total_notional, avg_leverage.
- Visuals illustrate how PnL and leverage distributions vary across sentiment regimes.
