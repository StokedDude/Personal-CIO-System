# 🏔️ Personal CIO System

**Quantitative Market Regime Detection & Dynamic Capital Allocation**

## Overview

Personal CIO is a systematic market timing framework that answers one critical question: 
**"Should I be deployed in the market right now?"**

Unlike binary on/off systems, Personal CIO uses a three-state regime model that matches 
how professional traders actually manage risk:
- **OFF** (0%): Market conditions unfavorable - stay in cash
- **LIGHT** (30%): Cautious deployment - selective high-quality setups only  
- **ON** (70%): Favorable conditions - full allocation to swing positions

## Key Features

- **Multi-Component Regime Analysis**
  - Trend strength (SPY/QQQ price vs moving averages)
  - Volatility assessment (VIX levels + term structure)
  - Market breadth (equal-weight vs cap-weight divergence)
  - Drawdown protection (distance from recent highs)

- **Hysteresis Mechanism**
  - Prevents whipsaw by requiring 3-day confirmation
  - Smooth transitions between states
  - Reduces false signals in choppy markets

- **Backtested Performance (2003-2026)**
  - 7.24% CAGR with -14% max drawdown
  - vs SPY: 10.20% CAGR with -56% max drawdown
  - Higher sleep-adjusted alpha: avoid catastrophic losses

- **Zero Configuration Required**
  - Automatically downloads market data (yfinance)
  - No manual data preparation
  - One-click execution in Google Colab
  - Complete analysis in 2 minutes

## Use Cases

✅ **Swing Traders**: Know when market conditions favor swing positions  
✅ **Portfolio Managers**: Dynamic allocation based on regime  
✅ **Risk Managers**: Systematic drawdown protection  
✅ **Discretionary Traders**: Quantified overlay for subjective decisions  

## What You Get

- Current regime state with confidence metrics
- Historical backtest with equity curves
- Regime transitions timeline
- Performance by regime analysis
- Visual dashboard (equity, drawdown, component breakdown)
- Exportable data for further analysis

## Philosophy

**Not maximizing returns. Minimizing regret.**

The goal isn't to beat SPY in bull markets. The goal is to avoid being fully deployed 
during the 2008 crisis, 2020 crash, or 2022 bear market while participating in 
favorable conditions.

Designed for traders who value:
- **Capital preservation** over maximum returns
- **Controlled drawdowns** over CAGR optimization
- **Sleep quality** over FOMO

## Quick Start

1. Upload notebook to Google Colab
2. Runtime → Run all
3. Wait 2 minutes (zero configuration needed)
4. Check Section 8 for current regime
5. Apply allocation to your strategy

No installation. No API keys. No data prep.

## Technical Details

- **Language**: Python 3.10+
- **Dependencies**: yfinance, pandas, numpy, matplotlib
- **Data**: SPY, QQQ, RSP, VIX (auto-downloaded)
- **Lookback**: 252 trading days (1 year)
- **Rebalance**: Daily monitoring, weekly execution

## Integration

Works with any stock selection system:
- CANSLIM screening
- Fundamental analysis
- Technical breakouts  
- Momentum strategies
- Your discretionary approach

The regime tells you **WHEN** to deploy.
Your strategy tells you **WHAT** to buy.

## Author Notes

Built for traders who know that **the best trade is sometimes no trade**. 

Originally developed to solve the problem: "My stock picks are good, but my timing 
sucks." Now answers: "Is today a good day to be in the market?"

Mountain biker analogy: You wouldn't ride the gnarliest line in wet conditions, 
even if you have the skill. Same principle for trading.

## License

MIT License - Use freely, modify as needed, trade at your own risk

---

*Not financial advice. Past performance doesn't guarantee future results. 
But it does suggest there are better and worse times to deploy capital.*
```

---

## 2. CANSLIM Signal Booster V6

### Short Description (for GitHub repo title/subtitle)
```
CANSLIM Signal Booster V6 - Quantitative Stock Screening Framework
Automated technical analysis that scores growth stocks using true 52-week highs, 
relative strength analysis, and volume quality metrics aligned with CANSLIM methodology
