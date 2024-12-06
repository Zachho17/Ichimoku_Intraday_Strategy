# Ichimoku intraday indicator strategy

## Summary
This strategy is built upon the usage of ichimoku indicator. There are numerous strategies that can be derived from ichimoku indicators, this strategy however attempts to combine multiple signals from ichimoku. By waiting for multiple signal before making a trade entry, I hope that it can improve the profitability of the ichimoku strategy that only relies on single signal. 
 
Below signals from the ichimoku have been taken into consideration for this strategy:
1. TenKan line vs Kijun line
2. Senkou span, or cloud crossover
3. current price vs ichimoku cloud
4. Chikou line vs historical price

The idea here is, only the above four "rules" are met, should the strategy triggers respective action, either long or short or stay flat. Once a change in signal is observed, a respective action will be taken.  

It is worth noting that this strategy does not have any mechanical stop-loss or take-profit level. All actions are determined by the pre-set rules. Such setting in general might expose to certain risk of ruin. However, any position opened for this strategy will only stay open if the above four rules continue to be applied. In the event when any one of the rules are not fullfiled, a change in signal would be triggered and position will be squared.  

Based on such set up, this strategy might work best during the regime with medium to long term extension in price action. It will not work during a relatively tight range market, where it might be more exposed to false signal. 

(To be continued)

## Workflow

## Challenges
