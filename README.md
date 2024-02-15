# TPS Golden Cross EA

This is the code for the TPS Golden Cross EA, developed by Forex Robot Easy Team. This Expert Advisor (EA) is designed to trade the Golden Cross pattern in the forex market.

## Input Parameters

- ShortTermMA: Short-term moving average period (default: 20)
- LongTermMA: Long-term moving average period (default: 50)
- LotSize: Default lot size (default: 0.01)
- StopLoss: Stop loss level in pips (default: 30.0)
- TrailingStop: Trailing stop level in pips (default: 20.0)

## Expert Initialization

The `OnInit()` function is called during the initialization of the EA. You can add any initialization code here if needed.

## Expert Deinitialization

The `OnDeinit()` function is called when the EA is being removed from the chart or during the terminal shutdown. You can add any deinitialization code here if needed.

## Expert Tick

The `OnTick()` function is called on every tick received by the EA. It detects the Golden Cross pattern and executes buy trades accordingly. Additional code can be added to detect and execute sell trades if needed.

## Execute Buy Trade

The `ExecuteTrade()` function is responsible for executing buy trades. It calculates the trade size based on the lot size and places a buy order at the current Ask price. Additional code can be added to execute sell trades if needed.

## Calculate Moving Average

The `GetMA()` function is used to calculate the moving average based on the specified period. You can add the code to calculate the moving average here.

## Check for Crossover

The `CrossOver()` function checks if there is a crossover between two moving averages. You can add the code to check for the crossover here.

## Convert Lot Size to Volume

The `LotsToVolume()` function converts the lot size to volume. You can add the code to convert the lot size to volume here.

For detailed reviews and trading results of this product, visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/tps-golden-cross-ea-review-optimizing-forex-trades/). Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.
