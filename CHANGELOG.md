# Changelog

## [1.0.0] - 2026-10-25

### Added
- Higher-timeframe candle ranges (CRT) for nine timeframes: H1, H4, H6, D1, W1, 1M, 3M, 6M, 12M
- Separate menu group for every timeframe: show toggle, color, line width, line style
- High and low lines with labels (for example `H6 H`, `H6 L`)
- Range logic: a range stays active while following candles stay inside it, a breakout or a new candle outside the range starts a new range
- Automatic hiding of timeframes lower than the chart timeframe
- 18 alert conditions: bullish and bearish touch for every timeframe
