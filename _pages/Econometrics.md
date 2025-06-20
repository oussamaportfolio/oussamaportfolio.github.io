---
permalink: /econometrics/
title: "Econometrics"
---

## ⬛ Do Cryptocurrencies Outperform the Market?  
  
<iframe src="https://drive.google.com/file/d/11jlfMQnVzUomAjueXRYYrr17PR0khLKi/preview" width="640" height="480" allow="autoplay"></iframe>
<br>
**Overview**

This report investigates whether cryptocurrencies can serve as viable investment assets by analyzing the performance of five cryptos (Bitcoin, Digibyte, Litecoin, Maidsafecoin, and NXT) from 2016 to 2019, compared to the S&P 500.

All computations and visualizations were done in **MATLAB**, including return calculations, performance ratios, and portfolio comparisons. The study also incorporates volatility measures and correlation with market fear (VIX) to assess diversification potential.

**Key Findings**

- Cryptocurrencies significantly outperformed the market in 2016–2017 but showed extreme volatility starting in 2018.  
- An equally weighted crypto portfolio delivered strong returns while reducing idiosyncratic risk.  
- Performance ratios (Sharpe, Sortino, Jensen’s Alpha) indicated attractive risk-adjusted returns, albeit with considerable downside exposure.  
- Low correlation with the S&P 500 and the VIX suggested strong diversification benefits—if managed with caution.

---

## ⬛ Industry Exposure to Fama-French Risk Factors  

<iframe src="https://drive.google.com/file/d/1oqF2FgoGdnohuMzJ-usEUn6tnMwWti-S/preview" width="640" height="480" allow="autoplay"></iframe>
<br>
**Overview**

This project applies the five-factor Fama-French model to 48 U.S. industry portfolios over a 25-year period.

The analysis was conducted entirely in **Python**, using two-pass regressions to estimate beta exposures and compute risk premia both statically and over rolling windows. Visualizations were created to track the evolution of factor sensitivity through time.

**Key Findings**

- Market beta remains dominant, but its relative importance declined post-2010.  
- The HML (value) factor produced negative risk premia after 2010, reflecting the rise of growth stocks.  
- SMB (size) became less stable after 2015, influenced by the increasing dominance of mega-cap stocks.  
- RMW (profitability) and CMA (investment) factors displayed divergent behavior post-2020, consistent with macroeconomic regime shifts.

---

## ⬛ Which Portfolio Strategy Truly Outperforms?  
  
<iframe src="https://drive.google.com/file/d/19DmnNegsyYVyhsX7PfXf7HNw9h-fV7Dp/preview" width="640" height="480" allow="autoplay"></iframe>
<br>
**Overview**

This report evaluates several portfolio construction strategies applied to ten low-correlation U.S. industry portfolios.

Using **Python**, we implemented and compared equal-weighted, minimum variance, maximum Sharpe, and mean-variance portfolios — both in long-only and long-short formats. The strategies were tested dynamically using historical and factor-based covariance matrices, with performance assessed using rolling windows and out-of-sample returns.

**Key Findings**

- Long-short portfolios optimized for historical Sharpe ratio consistently outperformed others in cumulative returns and Sharpe ratio.  
- Equal-weighted portfolios performed well during certain periods but lacked robustness across the full time span.  
- The S&P 500 served as a strong passive benchmark, especially during turbulent periods, but was ultimately outperformed by several optimized strategies.  
- Factor-based covariance matrices did not consistently outperform historical ones, highlighting the challenge of model calibration in dynamic environments.
