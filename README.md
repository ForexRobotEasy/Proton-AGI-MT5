# Proton AGI MT5

Proton AGI MT5 is a forex trading robot developed by the Forex Robot Easy Team. This algorithmic trading software is designed to automatically execute trades in the MetaTrader 5 platform.

Website: [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/proton-agi-mt5-review-buy-neuro-fx-ea-get-bonus-ea-free/)

## Code Description

The provided code is a sample implementation of the Proton AGI MT5 trading strategy. It utilizes the Trade and Math libraries to execute trades based on certain market conditions. The code is written in MQL5, the programming language used in the MetaTrader 5 platform.

### Constants

- `SYMBOL` - Specifies the trading symbol (e.g., 'EURUSD').
- `LOT_SIZE` - Defines the lot size for each trade.
- `TAKE_PROFIT` - Sets the take profit level in pips.
- `STOP_LOSS` - Sets the stop loss level in pips.

### Initialization

The `CTrade` object is initialized to perform trading operations.

### OnTick()

This function is called on each tick, providing the current market conditions. It calculates the stop loss and take profit levels based on the bid and ask prices.

If certain conditions are met, a buy or sell trade is placed using the `trade.Buy()` or `trade.Sell()` functions respectively.

### OnDeinit()

This function is called when the EA is being deactivated. It closes all open trades before shutting down.

## Product Description

Proton AGI MT5 is an algorithmic trading robot developed by the Forex Robot Easy Team. It is designed to automate trading operations in the forex market using the MetaTrader 5 platform.

This EA utilizes a sophisticated strategy to identify trading opportunities based on market conditions. It calculates the stop loss and take profit levels for each trade, allowing for precise risk management.

To use this product, simply install it in the MetaTrader 5 platform and configure the desired settings. The EA will then execute trades automatically according to the implemented strategy.

Please note that ForexRobotEasy is not the official developer of this product. We are solely providing a sample code that can work as described in the product. For more information and to find the official developer of this product, please refer to the [Proton AGI MT5 review](https://forexroboteasy.com/forex-robot-review/proton-agi-mt5-review-buy-neuro-fx-ea-get-bonus-ea-free/) on Forex Robot Easy website.
