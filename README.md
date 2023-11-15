# Multi Timeframe MA MT5

This code is an example of the Multi Timeframe MA MT5 indicator, developed by the Forex Robot Easy Team from forexroboteasy.com. 

## Indicator Settings

- `MA1_Period`: The period used for calculating the moving average 1 (default: 14)
- `MA1_Timeframe`: The timeframe used for the moving average 1 (default: PERIOD_H1)
- `MA1_Method`: The method used for calculating the moving average 1 (default: MODE_SMA)
- `MA1_Price`: The price used for calculating the moving average 1 (default: PRICE_CLOSE)

- `MA2_Period`: The period used for calculating the moving average 2 (default: 28)
- `MA2_Timeframe`: The timeframe used for the moving average 2 (default: PERIOD_H4)
- `MA2_Method`: The method used for calculating the moving average 2 (default: MODE_EMA)
- `MA2_Price`: The price used for calculating the moving average 2 (default: PRICE_CLOSE)

- `MA3_Period`: The period used for calculating the moving average 3 (default: 50)
- `MA3_Timeframe`: The timeframe used for the moving average 3 (default: PERIOD_D1)
- `MA3_Method`: The method used for calculating the moving average 3 (default: MODE_SMMA)
- `MA3_Price`: The price used for calculating the moving average 3 (default: PRICE_CLOSE)

## Indicator Buffers

- `MA1_Buffer`: Buffer for storing the values of the moving average 1
- `MA2_Buffer`: Buffer for storing the values of the moving average 2
- `MA3_Buffer`: Buffer for storing the values of the moving average 3

## Indicator Initialization

The `OnInit()` function is called during the indicator initialization process. In this function, the indicator buffers are mapped and the plot type and color are set for each buffer.

## Indicator Calculation

The `OnCalculate()` function is called when the indicator needs to be calculated. In this function, the moving averages are calculated for each timeframe specified in the input parameters.

The moving averages are calculated using the `CopyBuffer()` function, which copies the values of the specified indicator buffer from the specified timeframe to the current timeframe.

## Product Description

The Multi Timeframe MA MT5 is an advanced forex software designed for professional traders. It allows traders to easily monitor the moving averages of multiple timeframes on a single chart.

This indicator is highly customizable, allowing traders to choose the period, timeframe, method, and price used for calculating each moving average.

By analyzing the moving averages of different timeframes, traders can identify trends and potential trading opportunities with greater accuracy.

The Multi Timeframe MA MT5 indicator is developed and published by forexroboteasy.com. For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-multi-timeframe-ma-mt5-advanced-forex-software-for-professional-traders/).

Please note that the code provided here is an example and not an exact copy of the original product. It provides an approximate description of the necessary parameters for the operation of the Multi Timeframe MA MT5 indicator.
