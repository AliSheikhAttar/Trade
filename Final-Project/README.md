## About the Project

In this project, we will use **volatility** and **time series analysis** to manage a portfolio. The ultimate goal is to improve portfolio performance by optimizing asset weights and comparing different prediction methods.

### 1. Data Collection and Processing

To build the portfolio, collect historical daily data for the following cryptocurrencies: **BTC-USD, ETH-USD, BNB-USD, XRP-USD** from **August 1, 2023**, to **December 1, 2024**.

Split the data into two parts:

- **Training Set**: From **August 1, 2023**, to **August 1, 2024**.
- **Test Set**: From **August 1, 2024**, to **December 1, 2024**.

Ensure that the data is clean and ready for processing.

### 2. Volatility Prediction

For all mentioned cryptocurrencies, consider two time windows for volatility estimation: **7-day** and **30-day**.

#### Part 1: Statistical Models (Volatility Forecasting)
In this section, use the following models to forecast volatility for all cryptocurrencies: **GARCH, EGARCH, FIGARCH**.

#### Part 2: Volatility Proxies
In this section, calculate volatility using several proxies, including:

- **Historical Volatility**  
- **Parkinson Volatility**  
- **Garman-Klass Volatility**  
- **Yang-Zhang Volatility**

Study the provided links for each estimator and implement their formulas. By the end of this section, you should have **14 volatility series** for each cryptocurrency.

### 3. Portfolio Optimization: Weighting and Optimization Methods

In this section, we will use the **Black-Litterman** method to optimize the portfolio. This method allows combining historical data and forward-looking views to allocate weights to assets.

#### Step 1: Aggregating Volatility Series
First, calculate the mean of the volatility series for each group of estimators. These groups include:

- **Statistical Models**: GARCH, EGARCH, FIGARCH.
- **Volatility Proxies**: Historical, Parkinson, Garman-Klass, Yang-Zhang.

For each group, calculate the mean of the volatility series (e.g., the mean of the 7-day and 30-day windows) to obtain a single series for each volatility estimation method.

#### Step 2: Portfolio Optimization for Each Group
Using the calculated mean values, perform portfolio optimization separately for each group:

- Use the **Black-Litterman** method to calculate optimal weights.
- The input to the model includes the mean volatility values.
- The optimization goal is to maximize the **Sharpe Ratio** using a **Buy and Hold** strategy.
- Design a mechanism to ensure portfolio diversification and avoid concentration of weights on specific assets.
- Save the optimal weights for each group (7 sets of weights in total).

### 4. Strategy and Portfolio Usage

In this section, consider a simple **Buy and Hold** daily strategy. For implementation, assume an initial capital of **$1000** and a **2% transaction cost**.

Next, apply this strategy to the portfolio with the weights obtained from the previous step. Note that this should be done for each group of weights, once for the training set and once for the test set. For each group, report the following metrics:

- **Sharpe Ratio**  
- **Net Profit**  
- **Max Drawdown**

### 5. Analysis of Results

Compare the reported metrics for each group of weights and volatility estimators. Which volatility series yields better results, and what do the obtained metrics mean for each group? Explain.

Finally, plot and explain the following charts for the group with the optimal output:

- **Equity**  
- **Portfolio Allocation**  
- **Volatility Dynamics Over Time**  
- **Confidence Intervals of Portfolio Estimates**  
- **Cumulative Returns**