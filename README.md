# Fear and Greed MT4

This is a custom indicator for MetaTrader 4 (MT4) called Fear and Greed. It is developed by Forex Robot Easy Team and can be found on their website [here](https://www.forexroboteasy.com).

## Indicator Initialization

The `OnInit()` function is the initialization function of the indicator. It sets up the indicator buffers and parameters. It adds two indicator buffers, `ExtMapBuffer1` and `ExtMapBuffer2`, which will be used to store the Fear and Greed levels. It sets the indicator style as solid lines with a width of 2, and colors them red and blue respectively. Finally, it sets an alert message to indicate that the indicator has been initialized successfully.

## Indicator Calculation

The `OnCalculate()` function is the iteration function of the indicator. It calculates the Fear and Greed levels and updates the indicator buffers accordingly. It takes the necessary parameters for calculation, such as the OHLC data and tick volume. It loops through the bars and calculates the Fear and Greed levels using the `CalculateFearLevel()` and `CalculateGreedLevel()` functions. It then updates the indicator buffers with the calculated levels. After that, it checks for pivot key zones using the `CheckPivotKeyZones()` function. Finally, it returns the total number of calculated bars.

## Fear and Greed Calculation

The `CalculateFearLevel()` and `CalculateGreedLevel()` functions are responsible for calculating the Fear and Greed levels. However, the code provided in these functions is just a placeholder and needs to be replaced with the actual calculation algorithms.

## Pivot Key Zones

The `CheckPivotKeyZones()` function is responsible for checking for pivot key zones. However, the code for this functionality is not provided and needs to be added separately.

Please note that Forex Robot Easy is not the official developer of this product. This code is just a sample and can work as described in the product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [here](https://forexroboteasy.com/forex-robot-review/fear-and-greed-mt4-review-reliable-forex-decision-aid/).
