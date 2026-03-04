# Capital Magnet Scanner - Sector & Industry Rotation Detector

A Jupyter notebook that identifies **where institutional capital is flowing** using Mansfield Relative Strength analysis.

## What It Does

Scans all major sectors and industries to find the ones **actively stealing capital** from the rest of the market — where relative strength is accelerating while others are decelerating.

## Key Metrics

| Metric | Meaning |
|--------|---------|
| **MRS** | Mansfield Relative Strength (0 = market performance) |
| **Mom 20d** | 20-day RS momentum — is the trend accelerating? |
| **vs MA** | RS vs its 20-day moving average — trend health check |
| **Rank Δ** | Rank change over 1 month — rotation targets |
| **Flow** | 🧲 MAGNET = gaining capital · 🚰 DRAIN = losing capital |
| **Score** | Composite — higher = stronger rotation candidate |

## View the Results

Click **"Open in nbviewer"** above or view the notebook directly on GitHub to see the latest scan results.

## Requirements

```
yfinance
pandas
altair
vegafusion
```

---
*Data sourced from Yahoo Finance. For educational purposes only — not financial advice.*
