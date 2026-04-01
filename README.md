Impact of U.S. Fed Rates on the Mexican Economy
A Vector Autoregression (VAR) Analysis
Overview
This project analyzes how U.S. Federal Reserve interest rate decisions propagate through the Mexican economy, affecting the exchange rate, inflation, domestic interest rates, and trade balance.
Built as part of my Economics degree at FES Aragón, UNAM — using 285 monthly observations (2000–2024) across 6 macroeconomic variables.
Key Findings

82% correlation between Fed rate and TIIE (Banxico rate) — confirming monetary policy spillover
91% correlation between exchange rate and CPI — exchange rate is Mexico's primary inflation driver
2022–2023 tightening cycle produced measurable peso depreciation and Banxico raising TIIE to 11.25%

Methodology

Stationarity testing (Augmented Dickey-Fuller)
Series differencing for non-stationary variables
Optimal lag selection (AIC/BIC criteria)
VAR model estimation
Correlation analysis

Variables
VariableSourceDescriptionFEDFREDU.S. Federal Funds RateTCBanxicoMXN/USD Exchange RateTIIEBanxicoMexico Interbank RateINPCINEGIConsumer Price IndexIMPBCBanxicoTrade Balance — ImportsEXPBCBanxicoTrade Balance — Exports
Stack

Language: Python 3.13
Libraries: pandas, statsmodels, matplotlib, seaborn
Model: Vector Autoregression (VAR)

Full Analysis
See ensayo_final.pdf for the complete written analysis (Spanish).
