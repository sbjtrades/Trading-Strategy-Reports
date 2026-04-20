# Trading Strategy Reports

Interactive backtesting reports and performance analysis for the 30-Sec OR Ladder Rotations strategy across multiple instruments.

## 🚀 Quick Start

**[View Interactive Reports Portal →](index.html)**

Toggle between **NQ/MNQ** and **ES/MES** instruments to explore detailed trading analysis including:
- 7-tab interactive dashboard (Ladder Overview, P&L, Progression Probability, Daily Reach, Time & Day Patterns, Risk & Reward, Trade Analysis)
- Profitability metrics & risk analysis
- Entry ladder performance
- Time-based performance patterns
- Directional analysis (Longs vs Shorts)

## Strategy Overview

### 30-Sec OR Ladder Rotations
A discretionary intraday strategy using 30-second Opening Range ladder rotations on CME E-mini futures.

**Available Instruments:**
- **NQ/MNQ** (Nasdaq 100) - 3-year backtest (7,027 trades) + weekly snapshots
- **ES/MES** (S&P 500) - Multi-year backtest + weekly snapshots (coming soon)

---

### NQ/MNQ Reports
- **3-Year Master**: Jun 15, 2023 → Apr 14, 2026 (7,027 trades)
- **Weekly Snapshots**: Latest week-by-week performance
- [View NQ/MNQ Reports →](30-sec-or-ladder-rotations/reports/)

### ES/MES Reports
- **Master Report**: Complete backtest analysis
- **Weekly Snapshots**: Coming soon
- [View ES/MES Reports →](es-mes/reports/)

---

## Technology

- **Backend**: Python backtester with pandas, numpy, plotly
- **Frontend**: Interactive HTML5 + Plotly.js
- **Hosting**: GitHub Pages (static hosting)
- **Data Source**: TradingView backtest exports

---

*Reports generated from live trading backtests. Strategy code maintained in separate private repository.*
