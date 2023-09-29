## [Project3: Monte Carlo Simulations](https://github.com/dsrichard97/montecarlo_analysis.git)
* Collaborators: Richard Diazdeleon, Nate Talampas
* Date: TBD

insert image here 

## Introduction
Monte Carlo simulations offer a robust and versatile framework for understanding the complex dynamics of financial markets. Named after the famous casino in Monaco, this technique allows us to model uncertainty and make probabilistic forecasts. In the context of stock price prediction for NVIDIA Corporation (NVDA) and ASML Holding N.V. (ASML), both of which are key players in the semiconductor industry, Monte Carlo simulations provide several advantages: Handling Complexity, Risk, Descision-making, and have a real-world calibration. 

Given the volatile nature of the technology sector and the high stakes involved in investment decisions, Monte Carlo simulations serve as an indispensable tool for investors and analysts alike. By employing this technique, one can gain nuanced insights into the future behavior of NVDA and ASML stocks, thereby making more informed investment decisions. However, it is important to note that this model is give some further inisights about the stock since real-world modeling requires other specific measures (Computational Power and Speed) to accurately describe the nature of the stock.

## Research Questions
* I.   What is the expected stock price trajectory for NVDA and ASML over a specified time horizon?
* II.  How do the risk profiles of NVDA and ASML compare, as measured by metrics such as Value at Risk (VaR) and Conditional Value at Risk (CVaR)?
* III. Can Monte Carlo simulations provide actionable insights for portfolio diversification involving NVDA and ASML stocks?

## Methodology
* Data Exploration:
  * a. Fetch historical stock data for NVDA and ASML.
  * b. Perform exploratory data analysis to understand trends, seasonality, and volatility.
* Statistical Tests:Conduct unit root tests to check for stationarity and use Granger causality tests to explore potential leading indicators. 
* Model Fitting:
  * a. Calibrate Monte Carlo simulations using historical data and relevant financial metrics.
  * b. Utilize Geometric Brownian Motion (GBM) for stock price simulations.
* Model Comparison: We can create compute simulated trajectories of NVDA and ASML. This would allow us to evaluate the models based on risk and return metrics.
## Key Findings


##  Python Code and Libraries Used
* Python Version: 3.9
* Libraries: yfinance, numpy, matplotlib, scipy, pandas

## Future Work
[Utilize: Automatic differentiable Monte Carlo: Theory and application](https://journals.aps.org/prresearch/references/10.1103/PhysRevResearch.5.033041)

## References
PowerPoint:

Tableau: 

Workflow: 

Dataset:  https://finance.yahoo.com/quote/ASML/history?p=ASML
https://finance.yahoo.com/quote/NVDA?p=NVDA&.tsrc=fin-srch


Other References: 

