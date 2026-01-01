# nepse-quantitative-analysis
A comprehensive data science project analyzing the Nepal Stock Exchange (NEPSE). This project processes over 250,000 trading records across 124 companies to identify market efficiencies, systematic risk, and investment opportunities using modern financial metrics.
🛠️ The Pipeline: What I Performed
    1. Data Cleaning & Engineering
Standardization: Converted raw datatypes (Dates/Floats) for 250,000+ records.

Return Engine: Calculated daily percentage change and log returns to measure asset growth.

Integrity Checks: Filtered zero-volume days and price gaps to ensure statistical accuracy.
     2. Performed EDA which included
.Summary statistics (close_min,max,std), daily avg return,volatility to identify high value,volume and risk companies
.Conducted Distribution Analysis to understand general market behavior and detect outliers.
.Conducted time-series analysis to detect growth trends as well as moving averages.
.Identified top losers and top gainersfor the latest trading day
.Calculated volatility per company using standard deviation of daily returns.

   3. Risk & Efficiency ModelingVolatility Analysis: Calculated standard deviation to quantify the "swing" risk of each ticker.Sharpe Ratio: Measured Risk-Adjusted Return to identify "Alpha Leaders" (Sharpe > 1.0).
   4. Market Sensitivity & Momentum
Beta Calculation: Determined stock sensitivity relative to the broad market index.
RSI Implementation: Developed a 14-day Relative Strength Index (RSI) to detect overbought/oversold conditions.
   5. Created a Visual Strategy Dashboard for Efficiency Map ie scatter visualization distinguishing high-reward/low-risk assets.

#  How to Run
Clone the repository.

Install dependencies: pip install pandas matplotlib seaborn numpy.

Open NEPSE_Analysis.ipynb in VS Code or Jupyter.
