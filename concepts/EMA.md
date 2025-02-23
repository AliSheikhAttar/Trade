# EMA (Exponential Moving Average)

What Is an Exponential Moving Average (EMA)?
An exponential moving average (EMA) is a type of moving average (MA) that places a greater weight and significance on the most recent data points.1 The exponential moving average is also referred to as the exponentially weighted moving average. An exponentially weighted moving average reacts more significantly to recent price changes than a simple moving average simple moving average (SMA), which applies an equal weight to all observations in the period.

- Key Takeaways
The EMA is a moving average that places a greater weight and significance on the most recent data points.
Like all moving averages, this technical indicator is used to produce buy and sell signals based on crossovers and divergences from the historical average.
Traders often use several different EMA lengths, such as 10-day, 50-day, and 200-day moving averages.

Formula for Exponential Moving Average (EMA)
  
EMA Today = (Value Today ∗ ( Smoothing/ 1+Days )) + EMA Yesterday ∗(1−( Smoothing / 1+Days))
​ 
where:
EMA=Exponential moving average

While there are many possible choices for the smoothing factor, the most common choice is:

Smoothing = 2
That gives the most recent observation more weight. If the smoothing factor is increased, more recent observations have more influence on the EMA.

- Calculating the EMA
Calculating the EMA requires one more observation than the SMA. Suppose that you want to use 20 days as the number of observations for the EMA. Then, you must wait until the 20th day to obtain the SMA. On the 21st day, you can then use the SMA from the previous day as the first EMA for yesterday.

The calculation for the SMA is straightforward. It is simply the sum of the stock's closing prices during a time period, divided by the number of observations for that period. For example, a 20-day SMA is just the sum of the closing prices for the past 20 trading days, divided by 20.2

Next, you must calculate the multiplier for smoothing (weighting) the EMA, which typically follows the formula: [2 ÷ (number of observations + 1)]. For a 20-day moving average, the multiplier would be [2/(20+1)]= 0.0952.

Finally, the following formula is used to calculate the current EMA:3

EMA = Closing price x multiplier + EMA (previous day) x (1-multiplier)
The EMA gives a higher weight to recent prices, while the SMA assigns equal weight to all values. The weighting given to the most recent price is greater for a shorter-period EMA than for a longer-period EMA.4 For example, an 18.18% multiplier is applied to the most recent price data for a 10-period EMA, while the weight is only 9.52% for a 20-period EMA.

There are also slight variations of the EMA arrived at by using the open, high, low, or median price instead of using the closing price.

- What Does the EMA Tell You?
The 12- and 26-day exponential moving averages (EMAs) are often the most quoted and analyzed short-term averages. The 12- and 26-day are used to create indicators like the moving average convergence divergence (MACD) and the percentage price oscillator (PPO).56 In general, the 50- and 200-day EMAs are used as indicators for long-term trends.3 When a stock price crosses its 200-day moving average, it is a technical signal that a reversal has occurred.

Traders who employ technical analysis find moving averages very useful and insightful when applied correctly. However, they also realize that these signals can create havoc when used improperly or misinterpreted. All the moving averages commonly used in technical analysis are lagging indicators.

Consequently, the conclusions drawn from applying a moving average to a particular market chart should be to confirm a market move or indicate its strength. The optimal time to enter the market often passes before a moving average shows that the trend has changed.

An EMA does serve to alleviate the negative impact of lags to some extent. Because the EMA calculation places more weight on the latest data, it “hugs” the price action a bit more tightly and reacts more quickly. This is desirable when an EMA is used to derive a trading entry signal.

Like all moving average indicators, EMAs are much better suited for trending markets. When the market is in a strong and sustained uptrend, the EMA indicator line will also show an uptrend and vice-versa for a downtrend. A vigilant trader will pay attention to both the direction of the EMA line and the relation of the rate of change from one bar to the next. For example, suppose the price action of a strong uptrend begins to flatten and reverse. From an opportunity cost point of view, it might be time to switch to a more bullish investment.

- Examples of How to Use the EMA
EMAs are commonly used in conjunction with other indicators to confirm significant market moves and to gauge their validity. For traders who trade intraday and fast-moving markets, the EMA is more applicable. Quite often, traders use EMAs to determine a trading bias. If an EMA on a daily chart shows a strong upward trend, an intraday trader’s strategy may be to trade only on the long side.

- The Difference Between EMA and SMA
The major difference between an EMA and an SMA is the sensitivity each one shows to changes in the data used in its calculation.

More specifically, the EMA gives higher weights to recent prices, while the SMA assigns equal weights to all values. The two averages are similar because they are interpreted in the same manner and are both commonly used by technical traders to smooth out price fluctuations.

Since EMAs place a higher weighting on recent data than on older data, they are more responsive to the latest price changes than SMAs. That makes the results from EMAs more timely and explains why they are preferred by many traders.7

- Limitations of the EMA
It is unclear whether or not more emphasis should be placed on the most recent days in the time period. Many traders believe that new data better reflects the current trend of the security. At the same time, others feel that overweighting recent dates creates a bias that leads to more false alarms.

Similarly, the EMA relies wholly on historical data. Many economists believe that markets are efficient, which means that current market prices already reflect all available information. If markets are indeed efficient, using historical data should tell us nothing about the future direction of asset prices.

- What Is a Good Exponential Moving Average?
The longer-day EMAs (i.e. 50 and 200-day) tend to be used more by long-term investors, while short-term investors tend to use 8- and 20-day EMAs. 

Is Exponential Moving Average Better Than Simple Moving Average?
The EMA focused more on recent price moves, which means it tends to respond more quickly to price changes than the SMA.7

- How Do You Read Exponential Moving Averages?
Investors tend to interpret a rising EMA as a support to price action and a falling EMA as a resistance. With that interpretation, investors look to buy when the price is near the rising EMA and sell when the price is near the falling EMA.

