# Hyperliquid_Sentiment_Analysis_Krutibandhu_Bhol
Data science pipeline analyzing 211k+ Hyperliquid trade executions against Bitcoin market sentiment metrics. Explores trader directional bias, fee optimization, and tail-risk drawdowns to derive automated quantitative trading strategies.

# Hyperliquid Trader Performance vs. Bitcoin Market Sentiment Analysis

A professional data science project focused on identifying systemic behavior patterns, analyzing operational execution efficiencies, mapping tail-risk drawdowns, and delivering sentiment-aware trading frameworks. This pipeline processes over 211,000 granular trade execution logs from the Hyperliquid decentralized perpetual exchange and matches them chronologically with macro-level Bitcoin Fear & Greed indices.

---

## 🚀 Project Architecture & Objectives

The primary goal of this repository is to determine how psychological market regimes affect professional trading performance. The analysis moves past simple generalizations to expose concrete trading biases and hidden mathematical matrices across different sentiment profiles.

### Core Analytical Dimensions Explored:
1. **Trader Directional Bias:** Evaluating whether market participants exhibit herd mentality (momentum-chasing) or act as structural contrarians.
2. **Operational Fee vs. Profit Optimization:** Quantifying real capital efficiency by analyzing transaction fee drag relative to absolute realized net profits.
3. **Tail-Risk Management:** Mapping the standard deviation curves ($\sigma$) and extreme single-trade drawdowns across varying market climates to optimize stop-loss parameters.

---

## 📊 Empirical Findings Summary

* **The Alpha Window:** Strategies deployed during moderate **Fear** windows exhibit the highest historical statistical edge and cleanest win-rate performance (~56.8%).
* **The Breakout Trap:** The largest systemic tail-risk drawdown event ($-\$117,990$) unexpectedly occurs during initial **Greed** breakout phases rather than euphoric market peaks, highlighting an over-leveraged retail herd chasing premature trends.
* **The Neutral Range Churn:** Range-bound **Neutral** regimes generate the worst operational fee-to-profit ratio (3.05%), indicating heavy over-trading of local low-volatility noise.
* **Counter-Cyclical Execution:** Successful participants in this dataset act as counter-cyclical market makers—net-buying panic capitulations under *Extreme Fear* (51.1%) and aggressively distributing shorts or taking profit into *Extreme Greed* market tops (55.1%).

---

## 🛠️ Tech Stack & Methodology

This production-grade repository is built using standard Python data science architecture:
* **Pandas:** Handles large-scale dataset vector-processing, structural chronological string parsing (IST conversion), and multi-metric aggregations.
* **Matplotlib & Seaborn:** Custom-themed, high-definition data charts mapping distribution spreads.
* **Jupyter Notebook / HTML:** Interactive notebooks natively embedding outputs, visualization rendering, and inline markdown documentation.
