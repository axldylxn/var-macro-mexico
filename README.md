\# Impact of U.S. Fed Rates on the Mexican Economy

\### A Vector Autoregression (VAR) Analysis



\## Overview

This project analyzes how U.S. Federal Reserve interest rate decisions 

propagate through the Mexican economy, affecting the exchange rate, 

inflation, domestic interest rates, and trade balance.



Built as part of my Economics degree at FES Aragón, UNAM — using 

285 monthly observations (2000–2024) across 6 macroeconomic variables.



\## Key Findings

\- \*\*82% correlation\*\* between Fed rate and TIIE (Banxico rate) — 

&#x20; confirming monetary policy spillover

\- \*\*91% correlation\*\* between exchange rate and CPI — 

&#x20; exchange rate is Mexico's primary inflation driver

\- \*\*2022–2023 tightening cycle\*\* produced a 23% peso depreciation 

&#x20; and Banxico raising TIIE to 11.25%



\## Methodology

1\. Stationarity testing (Augmented Dickey-Fuller)

2\. Series differencing for non-stationary variables

3\. Optimal lag selection (AIC/BIC criteria)

4\. VAR model estimation

5\. Correlation analysis and impulse response functions



\## Variables

| Variable | Source | Description |

|----------|--------|-------------|

| FED | FRED | U.S. Federal Funds Rate |

| TC | Banxico | MXN/USD Exchange Rate |

| TIIE | Banxico | Mexico Interbank Rate |

| INPC | INEGI | Consumer Price Index |

| IMPBC | Banxico | Trade Balance — Imports |

| EXPBC | Banxico | Trade Balance — Exports |



\## Stack

\- \*\*Language:\*\* Python 3.13

\- \*\*Libraries:\*\* pandas, statsmodels, matplotlib, seaborn

\- \*\*Model:\*\* Vector Autoregression (VAR)



\## How to Run

```bash

git clone https://github.com/axldylxn/var-macro-mexico

cd var-macro-mexico

pip install -r requirements.txt

jupyter notebook notebooks/var\_model.ipynb

```



\## Full Analysis

See `ensayo\_final.pdf` for the complete written analysis (Spanish).

