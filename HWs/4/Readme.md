Here is the translation of the provided content from the file named "تمرین سری چهارم.pdf":

---

**Exercise Series Four.pdf:**

**Faculty of Computer Engineering**

**Course: Algorithmic Trading**

**Instructor: Dr. Reza Entezari Maleki**

**Designer: Mohammad Mojtaba Asadi**

**Publication Date: 1403/09/03 (November 24, 2024)**

**Submission Date: 1403/09/16 (December 7, 2024)**

**Exercise Series Four**

---

**Regarding the Exercise**

- This exercise includes topics on:
  - Time Series Analysis

- Do not copy exercises from others under any circumstances. If cheating and copying are observed in the exercises, both parties will receive a score of zero.

---

**Section One**

- In the first step, connect to Yahoo Finance and collect historical data for five cryptocurrencies with the highest market value over a one-year period from November 1, 2023, to November 1, 2024, in three different time frames: daily, four-hourly, and hourly. Then, apply the ADF test on the collected dataset and determine whether these data are stationary with a probability of over 90%. In this part, we are looking for a cryptocurrency that is not stationary (if all five cryptocurrencies are stationary, refer to lower-value cryptocurrencies).

- Analyze the reason for the non-stationarity of this cryptocurrency and identify its factors. (Analysis can be done after completing the next two sections as well)

- For the time series discovered in the first step, plot the ACF and PACF charts and then determine the appropriate parameter p for the AR model, parameter q for the MA model, and parameters p and q for the ARMA model. As mentioned above, the data are subjected to a stationarity test over a one-year period. Now, use 11 months of this data for training the above three models (with parameters determined using ACF and PACF) and one remaining month for testing the model. Obtain the Mean Squared Error (MSE) and Mean Absolute Percentage Error (MAPE) criteria for the above models.

- Try to make this time series stationary using the methods discussed in class and remove the effects of various factors from the time series.

- Now, for the new stationary time series, test the AR, MA, and ARMA models again under the previous conditions and compare the results.

---

**Section Two**

- First, obtain data for the top ten cryptocurrencies over a one-year period from November 1, 2023, to November 1, 2024, through Yahoo Finance. Note that the data should be for a daily time frame.

- Then, examine whether the overall volatility in the upward intervals related to these data is greater or in the downward intervals. Analyze the result and explain the relationship of your conclusion with the ARCH and GARCH models.

---

**Section Three**

- In this section, you should use the ARCH and GARCH models to make a prediction of the future price of the desired cryptocurrency and then design a buy and sell strategy using this obtained information.

- First, obtain data for Bitcoin and Ethereum cryptocurrencies over a one-year period from November 1, 2023, to November 1, 2024, through Yahoo Finance. Note that the data should be for a four-hourly time frame. The last month of this data should be used for validation. (Note that it is necessary to set aside another period for testing besides this month)

1. Then, fit the ARMA model with appropriate parameters to your training data returns.

2. Now, calculate the errors between the obtained model and the returns (this comparison should be done on test data) and provide it to the ARCH model. For this, calculate the appropriate parameters for ARCH.

3. Then, similar to the previous step, fit the GARCH model with appropriate parameters to the remaining (error) returns.

- In this part, we intend to observe the differences in predictions in different models. Our strategies should be used in three different scenarios:
  1. Only the ARMA model
  2. Using both ARMA and ARCH models
  3. Using both ARMA and GARCH models

- For calculation and prediction on test data, repeat the three-stage process mentioned using the rolling prediction technique. Implement your buy and sell strategies using the three obtained predictions.

- Finally, trade using the strategies with an initial capital of $1000 and ultimately calculate the Sharpe ratio for each of your three strategies and explain the reasons for the results in detail.

---

**Section Four**

- First, obtain data for the top ten cryptocurrencies over a one-year period from January 1, 2023, to January 1, 2024, through Yahoo Finance. Note that the data should be for a daily time frame.

- Then, using the Granger causality test, find the two cryptocurrencies with the highest dependency on each other and plot their graphs and compare them with each other.

**Exercise Submission Notes:**

- Implement this exercise using Python programming language in a Jupyter notebook format.

- Package the Jupyter notebook file related to the implementation, along with a Persian report, into a zip file and send it.

**Your report should include the following:**

1. Descriptions related to the implementation method
2. Descriptions related to the implementation method of each criterion

---