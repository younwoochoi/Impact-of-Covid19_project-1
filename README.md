## Impact of COVID-19: A Comparative Portfolio Analysis and a glimpse into the future

#### Comparative Analysis of Custom Portfolio, Fintech ETF and S&P 500

- **Daily & Cumulative Returns**: Daily returns show higher variations in returns for the custom portfolio whereas the cumulative returns show that both FINX and Custom portfolio outperformed the benchmark S&P 500. 

 ![Daily returns](image/Daily_returns.JPG)
 ![Cumulative returns](image/cum_returns.JPG)

- **Risk Analysis**: The standard deviation as well as the rolling 21-day standard deviation both show that the custom portfolio is more risky than FINX and the market.    

    - FINX - 0.021597
    - S&P 500 - 0.017911
    - Custom Portfolio - 0.021822

 ![Rolling std](image/rolling_std.JPG)  

- **Sharpe Ratios**: Based on return-to-risk one can note that the Fintech ETF had the highest Sharpe ratio.

 ![Sharpe Ratios](image/sharpe_ratio.JPG)   

#### 10-year performance of Custom portfolio, FINX ETF and the S&P 500: 

 Governments around the globe have already committed about $8 trillion to address the health, social and economic ravages of the COVID-19 pandemic. This price tag (which continues to grow) includes direct spending, equity injections, loans and guarantees. It is more than four times what all the countries on the planet collectively spent on military, weapons and war in 2019. It is a staggering 9.5% of pre-COVID global GDP.

 As we deal with and recover from this pandemic, we need to do so in a way that better prepares us to deal with future pandemics and other unpredictable but inevitable large-scale disasters, like very big earthquakes, tsunamis and hurricanes. 

 In the last 20 years, we've had six significant threats like SARS, MERS, Ebola, avian influenza and swine flu. One can therefore predict that there is no doubt we will see another stock market crash due to a large-scale disaster. 

 We don't know when the next market crash will happen. It is inevitable but we cannot predict with certainity but we can prepare for the future. Keeping that in mind, we have made an attempt to evaluate the performance of our custom portfolio, the fintech ETF and the S&P 500 for the next 10 years.

#### Monte Carlo Simulations:
 We performed Monte Carlo simulations on FINX ETF, S&P 500 and the custom portfolio for the next 10 years using historical data to perform a normally distributed random selection based on the sample mean and standard deviation of historical daily returns. 

![FINX Simulation](image/FINX_10years.JPG)

 Based on the simulations the target price for FINX after 10 years at a 90% confidence interval would be in the range of $40.69 - $539.93. The median price being $286.56 giving a return of 718.98% from the current price of $34.99(July 28, 2020)

![S&P 500 Simulation](image/sp500_10years.JPG)

 Based on the simulations, the target for S&P 500 after 10 years at a 90% confidence interval would be in the range of 2,484.59 - 10,045.66. The median being 5,696.54 giving a return of 77% from the current level of 3,218.44(July 28, 2020) 

 ![Custom Portfolio Simulation](image/monte_carlo.JPG)

 Based on the simulations the returns for Custom Portfolio after 10 years at a 90% confidence interval would be in the range of 2.19% - 20.04%. The median being 6.93%.

#### Actions to take before the next crash:

 How can we get ready for another major event? We can do that by keeping cash ready for 3 important things:

- **Emergency Savings**:  Recessions, job losses, illnesses, natural disasters, and a lot of other things can happen unexpectedly. In addition to having appropriate kinds of and amounts of insurance, you should aim to have cash savings that can cover six or more months of basic living expenses.

- **Expected expenses**: While your emergency savings is preparing for unexpected near-term needs, one should also prepare your portfolio for those expected needs coming up soon. Investments away from stocks and into high-quality bonds. The goal is having a few years' expenses in these low-volatility assets before you need them.

- **Investing to profit from the next crash**:Setting aside cash to invest in the next crash. A small portion of ones portfolio say 5% of what would normally be investment in stocks can be held in cash to invest when the market drops quickly.

 Investing half this cash when stocks fall 10% from a recent high, investing half of the remaining cash when stocks fall 20% and the rest at the 30% drop.

 Stock market history shows that we see 10% declines about once every year or two, 20% declines about once every five to seven years; a 30% decline has happened only six times. Going by history, one can use this probability to take advantage of future downturns in the market.

**S&P 500 Historical Annual Returns**

 ![S&P500 Historical](image/sp-500-historical-annual-returns.png)
 Source: *https://www.macrotrends.net/2526/sp-500-historical-annual-returns*

### Data Used for Analysis

1. Out of a list of [Top 25 S&P 500](image/stock_list.png) companies, 5 stocks were chosen(highlighted) based on high dividend payments and sector diversification. 

2. Global X fintech ETF the oldest and most established fintech ETF was chosen from a list of [Top ETFs](image/etf_list.png).

3. COVID-19 API was used for coronavirus data for USA.

4. Tabulate was used to Pretty-print tabular data in Python, a library and a command-line utility.

