# TME Trend & Momentum Engine

**Principal Architect:** Ertiza Abbas  
**Domain Expertise:** Macroeconomic, Geopolitical & Quantitative Systems Analysis (14+ Years Active Market Tenure)  
**Deployment Base:** Seoul $\rightleftharpoons$ Singapore  
**Contact / Research Mentorship Inquiries:** [abbasertiza@gmail.com](mailto:abbasertiza@gmail.com)

---

##  Algorithmic System Overview & Philosophy

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

##  Mathematical Pipeline & Filter Framework

Every evening at the market close, the engine processes asset matrices through a three-layer qualification framework before generating order matrices.


##  Environment Provisioning & Quick Start

The repository includes a cross-platform Bash bootstrapper (`deploy.sh`) that checks for a clean Python installation, builds an isolated virtual environment (`.venv`), upgrades your system compilers, and installs every package required to execute the models with a single terminal command.

### Automated Local Deployment

To provision your workspace environment automatically using Git Bash (Windows), macOS, or Linux, execute the following sequence inside your local directory:

```bash
# 1. Provide local execution permissions to the bootstrapper script
chmod +x deploy.sh

# 2. Run the automated deployment pipeline
./deploy.sh
```

### Manual Operational Interface

Once the deployment sequence signals a successful completion state, activate your virtual environment partition and open the interactive quantitative notebook workspace:

```bash
# Activate the isolated virtual environment sandbox
# For Windows (Git Bash):
source .venv/Scripts/activate

# For macOS / Linux:
source .venv/bin/activate

# Boot the Jupyter Lab workspace visualization console
jupyter lab
```

### Quick Start Code Engine Interface

To call the core framework or integrate your data pipelines inside a separate script file, import and run the system object:

```python
# Ingest the unified TME system framework
from tme_engine import UnifiedAbbasEngine

# Initialize the engine targeting a \$100,000 professional desk
tme_system = UnifiedAbbasEngine(initial_equity=100000.0, risk_parameter=0.01)

# Generate active matrix order book brackets across global watchlists
active_dashboard_df = tme_system.process_live_market_matrix()
print(active_dashboard_df.to_string(index=False))
```


