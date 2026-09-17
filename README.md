## The Data Portfolio — Big Mac Index Analysis

### Objective
This project applies purchasing power parity theory to The Economist's Big Mac Index to quantify currency valuation gaps and identify structural undervaluation and overvaluation across 57 countries from 2000 to 2026.

### Methodology
- Sourced Big Mac price data (57 countries, 45 periods, spanning July 2000 to July 2026) directly from The Economist's public GitHub repository
- Calculated implied Purchasing Power Parity (PPP) exchange rates from local Big Mac prices relative to the US dollar benchmark
- Derived valuation percentages to measure the degree of over/undervaluation for each currency
- Classified the dataset's structure across cross-sectional, time-series, and panel dimensions to guide appropriate analytical treatment
- Conducted a missing data diagnostic, identifying Russia's data discontinuation as Missing Not At Random (MNAR) given its geopolitically driven exclusion
- Built two core visualizations: a cross-sectional bar chart of currency valuations and a longitudinal time-series comparison of exchange rate deviations

### Key Findings
The analysis reveals persistent, structural mispricings rather than transient noise. The Swiss franc emerged as the most consistently overvalued currency in the sample, trading **41.8% above PPP-implied fair value** in the July 2024 cross-section. At the opposite end, the Japanese yen showed sustained undervaluation, registering below PPP fair value in every decade of the series — a pattern consistent with Japan's prolonged low-inflation, weak-currency macroeconomic environment.
