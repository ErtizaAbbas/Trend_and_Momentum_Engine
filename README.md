# TME Trend & Momentum Engine

**Principal Architect:** Ertiza Abbas  
**Domain Expertise:** Macroeconomic, Geopolitical & Quantitative Systems Analysis (14+ Years Active Market Tenure)  
**Deployment Base:** Seoul $\rightleftharpoons$ Singapore  
**Contact / Research Mentorship Inquiries:** [abbasertiza@gmail.com](mailto:abbasertiza@gmail.com)

---

## 1. Algorithmic System Overview & Philosophy

The **TME Trend & Momentum Engine** is an institutional-grade, multi-asset quantitative trading framework engineered specifically for professional desks and retail traders. Running strictly on the **Daily (1D) timeframe**, TME rejects the over-fitted assumptions of institutional black-box models. 

Instead, the model leverages structural price geometry, combining a multi-tier moving average regime with a non-linear velocity-adjusted momentum filter. This tactical system is validated by an Ordinary Least Squares (OLS) predictive machine learning regression layer, reducing directional risk and eliminating execution lag.

### Aligned Global Macro Watchlist Universe
The engine operates natively across a diverse, non-correlated multi-asset sandbox:
* **US Equities:** Dow Jones Index (`US30`), Nasdaq 100 Index (`US100`), DAX Index (`GER40`)
* **Commodities:** Gold COMEX Continuous Futures (`GOLD`)
* **G10 Foreign Exchange:** British Pound / Japanese Yen Spot (`GBPJPY`)
* **Sovereign Digital Assets:** Bitcoin / USD Spot (`BTCUSD`)
* **Singapore Regional Benchmarks:** Straits Times Index (`STI`), MSCI Singapore Index Futures (`SCI25`)

---

## 2. Mathematical Pipeline & Filter Framework

Every evening at the market close, the engine processes asset matrices through a three-layer qualification framework before generating order matrices.

