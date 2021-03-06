
-------------------------------------------------------------------------------------

## Indicators:

- **RSI MultiTimeframe:**
  Plots 3 RSI (Weekly, Daily, 4h) at the same time, regardless of the Chart Timeframe.
  Highlights in green (or red) if all RSI are oversold (or overbought).
  Can trigger custom oversold and overbought alerts.
  ![alt text](https://github.com/realhardworkingdeveloper/tradingview_indicators/blob/master/%5Bpreview%5D%20RSI%20MultiTimeframe%20I.png)
  
- **Volume Supply and Demand Zones:**
  Draws supply and demand zones based on 3 different volume threshold parameters.
  The timeframe of the script is fixed (you can change it in the options), 
  e.g. it is possible to keep Daily S/D zones while looking at 1h chart.
  ![alt text](https://github.com/realhardworkingdeveloper/tradingview_indicators/blob/master/%5Bpreview%5D%20Volume%20Supply%20and%20Demand%20Zones%20I.png)
  
- **MultiAverages MultiTimeframe:**
  Plots different kinds of averages ( EMA , SMA , SMMA , WMA , VWMA ) referred to a fixed timeframe, indipendent from   the one that you are watching, e.g. plot daily EMA on the 1h chart.
  Highlights the crossing of averages.
  ![alt text](https://github.com/realhardworkingdeveloper/tradingview_indicators/blob/master/%5Bpreview%5D%20MultiAverages%20MultiTimeframe%20I.png)
  

## Strategies:

- **Failure Swing (stop hunting):**
  This strategy is a first attempt to countertrade the false break of a key support/resistance.
  If a candle breaks the level, but it comes back before the close, it will trigger an order.
  The Stop Loss is in %, the Take Profit is near the EMA.
  The *volatility filter* is used to block new orders when the price is near the EMA.
  The *volatility adjustment* coefficients calibrate Stop Loss and Take Profit values according to the current volatility.
  ![alt text](https://github.com/realhardworkingdeveloper/tradingview_indicators/blob/master/%5Bpreview%5D%20Failure%20Swing%20S.png)
  
