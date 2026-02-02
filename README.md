# Market Risk and Return Analysis Using SPY as a Benchmark (Excel)

## Overview
This project analyzes the **risk, return, and risk-adjusted performance** of selected U.S. equities using historical price data, with **SPY (S&P 500 ETF)** serving as the market benchmark. The objective is to demonstrate applied data analysis skills using spreadsheet tools and core financial metrics commonly used in industry.

The analysis was performed using **Google Sheets** for data preparation and calculations, with final validation and visualization completed in **Microsoft Excel**.

---

## Assets Analyzed
- Apple Inc. (AAPL)  
- Microsoft Corp. (MSFT)  
- NVIDIA Corp. (NVDA)  
- JPMorgan Chase & Co. (JPM)  
- Bank of America (BAC)  
- Coca-Cola Co. (KO)  
- SPDR S&P 500 ETF (SPY) – benchmark  

---

## Data
- **Frequency:** Daily  
- **Metric:** Adjusted closing prices  
- **Time Horizon:** Multi-year historical period  
- **Benchmark:** SPY (S&P 500 ETF)  

---

## Methodology

### Daily Returns
Daily returns were calculated using:

\[
\text{Daily Return} = \frac{P_t - P_{t-1}}{P_{t-1}}
\]

This standardizes price changes and enables comparison across assets with different price levels.

---

### Annualized Return
Average daily returns were annualized using:

\[
\text{Annual Return} = \text{Average Daily Return} \times 252
\]

where 252 represents the approximate number of U.S. trading days per year.

---

### Annualized Volatility
Volatility was measured as the standard deviation of daily returns and annualized using:

\[
\text{Annual Volatility} = \text{Std Dev of Daily Returns} \times \sqrt{252}
\]

---

### Sharpe Ratio
Risk-adjusted performance was evaluated using the Sharpe ratio:

\[
\text{Sharpe Ratio} = \frac{\text{Annual Return} - R_f}{\text{Annual Volatility}}
\]

- **Risk-free rate assumption:** 3% annually  
- The rate approximates short-term U.S. Treasury yields and is stated explicitly for transparency.

Sharpe ratios are reported as **unitless decimal values**.

---

## Visualization
A **risk–return bubble chart** was created with:
- **X-axis:** Annual Volatility (Risk)  
- **Y-axis:** Annual Return  
- **Bubble size:** Sharpe Ratio  

This visualization allows simultaneous comparison of return, risk, and risk-adjusted efficiency relative to the SPY benchmark.

---

## Key Findings
- **NVDA** achieved the highest return and strongest risk-adjusted performance, accompanied by elevated volatility.
- **SPY** provided a balanced benchmark with competitive risk-adjusted returns and lower volatility than most individual equities.
- **KO** exhibited defensive characteristics with lower volatility and lower expected returns.
- Financial stocks (**JPM, BAC**) showed moderate returns with higher volatility relative to SPY.

These results highlight the importance of evaluating investments on a **risk-adjusted basis**, not returns alone.

---

## Tools Used
- Google Sheets – data cleaning and calculations  
- Microsoft Excel – visualization and bubble chart analysis  

---

## Skills Demonstrated
- Financial data analysis  
- Return and volatility modeling  
- Risk-adjusted performance evaluation  
- Spreadsheet modeling (Excel & Google Sheets)  
- Data visualization and analytical communication  

---

## Conclusion
By using SPY as a benchmark, this project demonstrates a structured approach to analyzing market risk and return that aligns with real-world financial and data analytics workflows. The combination of statistical analysis and visualization highlights trade-offs between risk and return and supports informed comparisons across assets.

---

## Future Improvements
- Incorporate beta and CAPM expected returns  
- Analyze rolling returns and rolling Sharpe ratios  
- Expand the analysis to sector ETFs  


