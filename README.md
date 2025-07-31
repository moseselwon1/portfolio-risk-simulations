portfolio-risk-simulations
Portfolio Risk Simulations: Monte Carlo & Historical VaR in Excel
This repository showcases two robust Excel-based financial models:
- Monte Carlo Simulation for Long-Term Portfolio Growth
- Monte Carlo + Historical VaR (Value at Risk) Simulator

Built entirely in Excel, these tools combine statistical logic with scenario-based analysis to quantify portfolio risk and performance potential — with no VBA or plugins required.

Models Included:
1. Monte Carlo InvestmentRetirement Simulation
- Simulates 40-year growth of a portfolio invested in the S&P 500
- Based on: $6,000 annual contribution, 7% return, 15% volatility
- Outputs include: median, mean, 5th–95th percentile forecasts
- 10,000 unique return paths generated using `NORM.INV(RAND())`
View: `Monte Carlo Investment Simulation.xlsx` and `MONTE CARLO NOTES.docx`

2. Value at Risk (VaR) Model – Monte Carlo & Historical
- Portfolio: $100,000 with 60% SPY and 40% BND
- Portfolio Variance: σ²_p = w₁²σ₁² + w₂²σ₂² + 2w₁w₂Cov₁₂
                           =60%^2 * SPY.ST.Dev.^2 + 40%^2 * BND.ST.Dev.^2 + 2*60%*40%*Covariance 
- Monte Carlo: 10,000 simulations using Z-scores + covariance
- Historical: Actual SPY/BND returns and P&L distribution
- Confidence Intervals: 90%, 95%, 99%

View: `Monte Carlo Method Value at Risk (VaR).xlsx` and `VALUE AT RISK NOTES.docx`

Both models reflect a probabilistic mindset, offering realistic stress-testing and long-tail insights, aligned with methodologies used in firms using Quant strategies to protect their assets.

Features
- No VBA: Fully Excel-native
- Histograms & Percentiles
- Stress-testing via confidence level toggles
- Clearly explained logic with notes included

 Author: Moses Elwon
 [T&M Financial Chronicles](https://tmfinancialchronicles.substack.com)  
 [LinkedIn](https://www.linkedin.com/in/your-link-here)  

