# Orders
## Definitions
1. Market Order
A market order is an immediate order to buy or sell an asset at the best available current price.
It’s fast, ensuring execution, but it may result in a slightly higher or lower price than expected, especially in volatile markets.
2. Limit Order
A limit order sets a specific price at which the trader wants to buy or sell.
It only executes if the asset’s market price reaches the specified limit price.
Limit orders give better price control but may not always execute if the market doesn’t reach the set price.
3. Stop Order (or Stop-Loss Order)
A stop order is an order to buy or sell once the asset hits a certain "stop" price.
Commonly used to limit losses or protect profits; for example, a trader could set a stop-loss to sell a stock if it falls below a certain price.
Once triggered, it turns into a market order.
4. Stop-Limit Order
This combines features of stop and limit orders.
When the stop price is hit, it triggers a limit order rather than a market order.
This means it will only execute within the specified limit, providing more control over the final execution price.
5. Trailing Stop Order
A trailing stop order automatically adjusts the stop price as the asset’s price moves favorably.
For example, if you set a trailing stop at 5%, it will automatically adjust upward as the asset’s price increases, locking in profits and limiting downside.
6. Good-Till-Canceled (GTC) Order
This order remains active until it is executed or the trader manually cancels it.
GTC orders allow traders to wait for their desired price without needing to monitor the market constantly.
7. Day Order
A day order is only valid for the trading day on which it’s placed.
If it isn’t executed by the end of the trading session, it is automatically canceled.
8. Fill or Kill (FOK) Order
This order instructs that the order must be executed immediately in its entirety or not at all.
Used when a trader wants to buy or sell a specific quantity but does not want a partial fill.
9. Immediate or Cancel (IOC) Order
Similar to FOK but allows partial execution.
Any portion of the order that can be filled immediately is, and the remaining unfilled part is canceled.
10. All or None (AON) Order
An order that specifies it must be entirely filled or not at all.
Often used for larger trades, ensuring that partial fills don’t happen when liquidity is low.
11. Bracket Orders
Used to place multiple orders that "bracket" an open position, typically with a target price and a stop-loss.
For example, if a stock is purchased, a bracket order could set a target to sell at a higher price and a stop-loss at a lower one to manage risk and profit.
12. Iceberg Order
An order that breaks up a large trade into smaller, more discrete parts to avoid showing the entire volume in the order book.
Useful in high-frequency trading (HFT) and for institutional traders who want to minimize market impact.
Each order type can be used depending on the strategy, risk tolerance, and goals of the trader.


## Examples
1. Market Order
Example: You want to buy shares of Company XYZ, which is currently trading at $50. You place a market order to buy 10 shares.

Because a market order executes immediately at the current market price, your broker fills the order at the best available price.

In this case, let’s say it fills at $50.10 because demand is high, and that’s the next available price. You end up with 10 shares at $50.10, slightly above your initial target, but the order is completed instantly.

Key Point: Market orders prioritize speed, but you might not get the exact price you see when placing the order.

2. Limit Order
Example: You want to buy shares of Company XYZ, which is trading at $50. You believe the price might dip to $48, so you place a limit order to buy 10 shares at $48.

This order will only execute if the price falls to $48 or below. If the price doesn’t reach $48, your order will remain open but unfilled.

If the price drops to $48 or lower, the order will fill automatically at that price or better.

Key Point: Limit orders give you price control, but execution isn’t guaranteed if the price doesn’t reach your target.

3. Stop Order (Stop-Loss Order)
Example: You own shares of Company XYZ, which you bought at $50, and the stock is now trading at $55. To protect your profits, you place a stop order to sell if the price drops to $52.

If the stock price falls to $52, the stop order triggers and turns into a market order to sell immediately at the next available price, which could be slightly above or below $52.

This is used as a “stop-loss” to limit losses or lock in gains, as it will sell if the price falls to your set stop level.

Key Point: Stop orders help limit losses but may sell slightly above or below the stop price because they convert to market orders when triggered.

4. Stop-Limit Order
Example: You own shares of Company XYZ, currently trading at $55, and want to protect against a price drop but avoid selling too low. You place a stop-limit order to sell with a stop price at $52 and a limit price at $51.

If the price falls to $52, the stop order is triggered, creating a limit order to sell at $51 or better.

If the stock price quickly drops below $51, the order may not fill, as it won’t execute below your limit price.

Key Point: Stop-limit orders provide more control over the execution price but can remain unfilled if the market moves quickly past your limit.

5. Trailing Stop Order
Example: You bought shares of Company XYZ at $50, and they are now trading at $55. You set a trailing stop order with a 5% trailing amount to sell if the stock drops 5% from its highest price.

As the stock rises, the trailing stop price adjusts to 5% below the highest price it reaches.

If the stock reaches $60, the trailing stop price will be $57 (5% below $60).

If the stock then falls to $57, the trailing stop triggers, and the shares sell automatically. But if the stock keeps rising, the trailing stop price will also rise.

Key Point: Trailing stops automatically adjust with the stock’s price movement, allowing for profit capture if the price goes up while still limiting losses.