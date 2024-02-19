# Chart Customizer

Chart Customizer is a trading software developed by the Forex Robot Easy Team to enhance the forex trading experience by providing advanced chart customization options. This software allows traders to modify their charts according to their preferences and trading strategies.

## Features

- Chart Type: The default chart type is a line chart, but traders can choose from other types such as bar, candlestick, or renko charts.
- Foreground Color: Traders can customize the foreground color of their charts to make it visually appealing or to highlight specific data.
- Chart Shift: Traders can apply a chart shift to move the chart horizontally, allowing them to focus on a specific time period.

## Global Variables

- `ChartType`: The chart type to be applied to all opened charts. The default value is set to CHART_LINE.
- `ForegroundColor`: The default foreground color of the charts. The default value is set to clrRed.

## Expert Advisor Functions

### OnInit()

This function is executed during expert advisor initialization. It applies the chart settings to all opened charts.

### OnDeinit(const int reason)

This function is executed during expert advisor deinitialization. It removes the chart customization and resets the chart settings to default.

### ChartApplySettings()

This function applies the chart settings to all opened charts. It iterates through all the charts and sets the chart type, foreground color, and chart shift according to the global variables.

### ChartRemoveCustomization()

This function removes the chart customization and resets the chart settings to default. It iterates through all the charts and resets the chart type, foreground color, and chart shift.

### Trading Functions

These functions are placeholders for market analysis, trend identification, entry signals, exit signals, risk management, and position sizing. Traders can add their own code to perform these functions based on their trading strategies.

## Product Description

[Chart Customizer](https://forexroboteasy.com/forex-robot-review/chart-customizer-review-revolutionize-forex-trading/) is a revolutionary trading software designed to enhance forex trading by providing advanced chart customization options. This software allows traders to customize their charts according to their preferences and trading strategies, resulting in a more personalized and effective trading experience.

With Chart Customizer, traders have the flexibility to choose from various chart types, including line, bar, candlestick, and renko charts. Additionally, they can customize the foreground color of their charts to make it visually appealing or to highlight specific data. Traders can also apply a chart shift to focus on a specific time period, enabling them to analyze the market more effectively.

The software is equipped with expert advisor functions that allow traders to perform market analysis, identify trends, generate entry and exit signals, manage risk, and determine position sizing. Traders can add their own code to these functions based on their trading strategies, making Chart Customizer a versatile tool for both beginner and experienced traders.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates how this product can work. For the official developer of this product, please refer to MQL5.
