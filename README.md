# VWAP With Alerts

This code calculates the Volume Weighted Average Price (VWAP) and generates alerts when the price crosses the VWAP line, indicating potential trading opportunities. The code is a custom indicator developed by the Forex Robot Easy Team from forexroboteasy.com.

## Indicator Inputs

- `period`: The period used to calculate the VWAP.
- `deviation`: The deviation used to generate alerts when the price crosses above or below the VWAP line.

## Global Variables

- `vwapBuffer[]`: The buffer to store the calculated VWAP values.
- `lastVwap`: The last calculated VWAP value.
- `alertGenerated`: A flag to track if an alert has been generated.

## Custom Indicator Initialization Function

The `OnInit()` function is used to initialize the custom indicator. It sets the indicator buffers and label.

## Custom Indicator Calculation Function

The `OnCalculate()` function is called to calculate the custom indicator values. It calculates the VWAP using the specified period and stores the values in the `vwapBuffer[]` array. It then checks if the current price crosses above or below the VWAP line with the specified deviation and generates an alert accordingly. The `alertGenerated` flag is used to ensure that alerts are only generated once per crossing.

To use this code, you can copy it into the MetaEditor of the MQL5 platform and compile it into an indicator. Once compiled, you can apply the indicator to a chart and it will calculate and display the VWAP line. Alerts will be generated when the price crosses the VWAP line.

Please note that forexroboteasy.com is not the official developer of this product. They have provided this code as a sample that can work as described in the product. To find the official developer of this product, you can use MQL5.

For detailed reviews and trading results of this product, you can visit https://forexroboteasy.com/forex-robot-review/vwap-with-alerts-forex-software-review-results/.
