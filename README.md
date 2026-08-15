# Gimmer

**Build, backtest, optimize, simulate, and run crypto trading bots from your own computer.**

Gimmer is a local-first desktop application for designing and operating automated cryptocurrency trading strategies. It combines strategy creation, historical backtesting, bounded parameter optimization, simulation, live execution, marketplace discovery, and runtime observability in one application for Windows, macOS, and Linux.

[Website](https://gimmer.com) · [Download](https://gimmer.com/download) · [Documentation](https://gimmer.com/docs) · [Hold-to-use pricing](https://gimmer.com/pricing) · [Public releases](https://github.com/GimmerBot/Gimmer/releases)

![Gimmer desktop strategy performance and monitoring](https://gimmer.com/assets/img/product/gimmer-strategy-performance.png)

## What you can do with Gimmer

- Build strategies with **Indicators, AI Decision, Code Editor, Swing, or Portfolio** engines.
- Configure Spot or Margin execution where the selected strategy engine supports it.
- Backtest strategies against historical OHLCV data and inspect return, drawdown, trades, open positions, and execution evidence.
- Compare bounded parameter combinations with the Strategy Optimizer while preserving the original strategy as a baseline.
- Run strategies in simulation before considering live execution.
- Monitor positions, orders, realized and open PnL, runtime activity, and application health.
- Discover traders and rent approved strategies through the Gimmer Marketplace.
- Use more than 80 technical indicators, including RSI, MACD, Bollinger Bands, Ichimoku, moving averages, ATR, ADX, MFI, OBV, PSAR, Stochastic RSI, and volatility tools.

## Current strategy engines

| Engine | Best suited for |
| --- | --- |
| Indicators | Rule-based strategies using technical indicators and explicit entry and exit logic. |
| AI Decision | Evidence-assisted decisions using a configured local AI runtime. |
| Code Editor | Typed custom strategy logic with Gimmer-managed execution and risk controls. |
| Swing | Drawdown entries, recovery rules, and portfolio-level profit exits. |
| Portfolio | Portfolio-aware allocation and multi-market workflows. |

## Desktop releases

Official binary releases are published for:

- **Windows** — 64-bit installer
- **macOS** — Apple silicon and Intel builds when available
- **Linux** — DEB packages for Debian/Ubuntu and RPM packages for Fedora/RHEL-compatible distributions

Use the [Gimmer download page](https://gimmer.com/download) to select the correct current build, or inspect every asset in [GitHub Releases](https://github.com/GimmerBot/Gimmer/releases).

## Local-first operation

The core runtime and operational database run on the user's computer. Connected features still communicate with their required services, including exchanges, market-data providers, signed IPFS workflows, the marketplace, and release delivery.

![Gimmer strategy workspace](https://gimmer.com/assets/img/product/gimmer-strategy-workspace.png)

## Learn the workflow

- [Quickstart](https://gimmer.com/docs/quickstart)
- [Create a strategy](https://gimmer.com/docs/create-strategy)
- [Indicators](https://gimmer.com/docs/indicators)
- [Code Editor](https://gimmer.com/docs/code-editor)
- [Swing](https://gimmer.com/docs/swing)
- [Strategy Optimizer](https://gimmer.com/docs/strategy-optimizer)
- [Simulation and live operation](https://gimmer.com/docs)

## Source and support

This public repository is the official release and issue hub for the current Gimmer desktop application. The current application source code is maintained privately. To report a reproducible problem, open a [GitHub issue](https://github.com/GimmerBot/Gimmer/issues) with the operating system, Gimmer version, relevant settings, and sanitized evidence.

## Risk notice

Automated trading does not remove market risk. Backtests, simulations, ratings, and historical performance do not guarantee future results. Live execution can be affected by exchange availability, liquidity, slippage, fees, network failures, configuration errors, and software or hardware conditions. Review the evidence and use simulation before putting live capital at risk.
