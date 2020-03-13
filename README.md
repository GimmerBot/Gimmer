## GIMMER - The smart way to trade [![GitHub version](https://badge.fury.io/gh/Gimmerbot%2FGimmer.svg)](https://badge.fury.io/gh/Gimmerbot%2FGimmer)
Gimmer is a tool for trade and algorithmic automation for Bitcoin and other cryptocurrencies.

## Open Sources for Code Editor 
https://github.com/GimmerBot/CodeEditor-Samples

## EXCHANGES
- [Binance](https://www.binance.com/en/register?ref=15629923)
- Poloniex
- Bitfinex
- Huobi
- HitBTC
- Kraken
- Others...

## FEATURES

- Spot Trading
- Margin Trading
- Binance Futures 125x
- Scalper
- Code Editor
- Mirror Arbitrage
- Triangular Arbitrage
- Lending
- Portfolio
- Websockets to trade in realtime
- Backtest and simulation mode
- Descentralized Marketplace
- Publish completely decentralized strategies
- Create different types of plans for rent
- Do backtests before renting a strategy
- Rent different strategies from different categories
- Marketplace search using several different types of filters
- Access rental strategies from anywhere at any time
- Vote for the best strategies
- Access list with all platform traders
- See trader-specific strategies sorted by popularity
- You can now execute backtest directly from the strategy screen.
- Start or stop robot execution directly from strategy list
- Top frame removal leaving the app with wider view
- Processor and memory usage displayed in backtest and activity log
- Improved backtest to get closer to the real market
- Improved design and background addition on all screens
- System memory usage optimization

# Decentralized dApp
![Webserver_UI](images/2020-03-12%20(5).png "Decentralized dApp")

# Strategy List
![Webserver UI](images/2020-03-12%20(8).png "Strategy List")

# Infinte Backtests
![Webserver UI](images/2020-03-12%20(16).png "Infinte Backtests")

# Strategy Builder
![Webserver UI](images/2020-03-12%20(12).png "Strategy Builder")

# Api Keys Valt
![Webserver UI](images/2020-03-12%20(26).png "Api Keys Valt")

# Code Editor
![Webserver UI](images/2020-03-12%20(2).png "Gimmer Code Editor for trade")

# Trader List
![Webserver UI](images/2020-03-12%20(13).png "Trader List")

# Marketplace
![Webserver UI](images/2020-03-12%20(14).png "Marketplace")

# Marketplace Backtest
![Webserver UI](images/2020-03-12%20(24).png "Marketplace Backtest")

# Lending
![Webserver UI](images/2020-03-12%20(25).png "Lending")

# Portfolio
![Webserver UI](images/2020-03-12%20(21).png "Portfolio")

# Triangular Arbitrage
![Webserver UI](images/2020-03-12%20(17).png "Triangular Arbitrage")

# Docs
![Webserver UI](images/2020-03-12%20(15).png "Documentation")


# INDICATORS

- ichimoku(historicalData: any[], conversionPeriod: number, basePeriod: number, laggingSpanPeriod: number, displacement?: number): Promise<any[]>;
- macd(close: number[], fastPeriod: number, slowPeriod: number, signalPeriod: number): Promise<any[]>;
- rsi(close: number[], length: number): Promise<any[]>;
- bbands(close: number[], period: number, stdDev: number): Promise<any[]>;
- ema(close: number[], period: number): Promise<any[]>;
- hma(close: number[], period: number): Promise<any[]>;
- wma(close: number[], period: number): Promise<any[]>;
- stoch(high: number[], low: number[], close: number[], kPeriod: number, kSlowing: number, dPeriod: number): Promise<any[]>;
- abs(close: number[]): Promise<any[]>;
- ad(high: number[], low: number[], close: number[], volume: number[]): Promise<any[]>;
- fisher(high: number[], low: number[], period: number): Promise<any[]>;
- add(input1: number[], input2: number[]): Promise<any[]>;
- adosc(high: number[], low: number[], close: number[], volume: number[], short: number, long: number): Promise<any[]>;
- adx(high: number[], low: number[], close: number[], period: number): Promise<any[]>;
- adxr(high: number[], low: number[], close: number[], period: number): Promise<any[]>;
- ao(high: number[], low: number[]): Promise<any[]>;
- apo(close: number[], short: number, long: number): Promise<any[]>;
- aroon(high: number[], low: number[], period: number): Promise<any[]>;
- aroonosc(high: number[], low: number[], period: number): Promise<any[]>;
- asin(close: number[]): Promise<any[]>;
- atan(close: number[]): Promise<any[]>;
- atr(high: number[], low: number[], close: number[], period: number): Promise<any[]>;
- avgprice(open: number[], high: number[], low: number[], close: number[]): Promise<any[]>;
- bop(open: number[], high: number[], low: number[], close: number[]): Promise<any[]>;
- cci(high: number[], low: number[], close: number[], period: number): Promise<any[]>;
- ceil(close: number[]): Promise<any[]>;
- cmo(close: number[]): Promise<any[]>;
- cos(close: number[]): Promise<any[]>;
- cosh(close: number[]): Promise<any[]>;
- crossany(input1: number[], input2: number[]): Promise<any[]>;
- crossover(input1: number[], input2: number[]): Promise<any[]>;
- cvi(high: number[], low: number[], period: number): Promise<any[]>;
- decay(close: number[], period: number): Promise<any[]>;
- dema(close: number[], period: number): Promise<any[]>;
- di(high: number[], low: number[], close: number[], period: number): Promise<any[]>;
- div(input1: number[], input2: number[]): Promise<any[]>;
- dm(high: number[], low: number[], period: number): Promise<any[]>;
- dpo(close: number[], period: number): Promise<any[]>;
- dx(high: number[], low: number[], close: number[], period: number): Promise<any[]>;
- edecay(close: number[], period: number): Promise<any[]>;
- emv(high: number[], low: number[], volume: number[]): Promise<any[]>;
- exp(close: number[]): Promise<any[]>;
- floor(close: number[]): Promise<any[]>;
- fosc(close: number[], period: number): Promise<any[]>;
- kama(close: number[], period: number): Promise<any[]>;
- kvo(high: number[], low: number[], close: number[], volume: number[], short: number, long: number): Promise<any[]>;
- lag(close: number[], period: number): Promise<any[]>;
- linreg(close: number[], period: number): Promise<any[]>;
- linregintercept(close: number[], period: number): Promise<any[]>;
- linregslope(close: number[], period: number): Promise<any[]>;
- ln(close: number[]): Promise<any[]>;
- log10(close: number[]): Promise<any[]>;
- marketfi(high: number[], low: number[], volume: number[]): Promise<any[]>;
- mass(high: number[], low: number[], period: number): Promise<any[]>;
- max(close: number[], period: number): Promise<any[]>;
- md(close: number[], period: number): Promise<any[]>;
- medprice(high: number[], low: number[]): Promise<any[]>;
- mfi(high: number[], low: number[], close: number[], volume: number[], period: number): Promise<any[]>;
- min(close: number[], period: number): Promise<any[]>;
- mom(close: number[], period: number): Promise<any[]>;
- msw(close: number[], period: number): Promise<any[]>;
- mul(input1: number[], input2: number[]): Promise<any[]>;
- natr(high: number[], low: number[], close: number[], period: number): Promise<any[]>;
- nvi(close: number[], volume: number[]): Promise<any[]>;
- obv(close: number[], volume: number[]): Promise<any[]>;
- ppo(close: number[], short: number, long: number): Promise<any[]>;
- psar(high: number[], low: number[], accelerationFactorStep: number, accelerationFactorMaximum: number): Promise<any[]>;
- pvi(close: number[], volume: number[]): Promise<any[]>;
- qstick(open: number[], close: number[], period: number): Promise<any[]>;
- roc(close: number[], period: number): Promise<any[]>;
- rocr(close: number[], period: number): Promise<any[]>;
- round(close: number[]): Promise<any[]>;
- sin(close: number[]): Promise<any[]>;
- sinh(close: number[]): Promise<any[]>;
- sma(close: number[], period: number): Promise<any[]>;
- sqrt(close: number[]): Promise<any[]>;
- stddev(close: number[], period: number): Promise<any[]>;
- stderr(close: number[], period: number): Promise<any[]>;
- stochrsi(close: number[], period: number): Promise<any[]>;
- sub(input1: number[], input2: number[]): Promise<any[]>;
- sum(close: number[], period: number): Promise<any[]>;
- tan(close: number[]): Promise<any[]>;
- tanh(close: number[]): Promise<any[]>;
- tema(close: number[], period: number): Promise<any[]>;
- todeg(close: number[]): Promise<any[]>;
- torad(close: number[]): Promise<any[]>;
- tr(high: number[], low: number[], close: number[]): Promise<any[]>;
- trima(close: number[], period: number): Promise<any[]>;
- trix(close: number[], period: number): Promise<any[]>;
- trunc(close: number[]): Promise<any[]>;
- tsf(close: number[], period: number): Promise<any[]>;
- typprice(high: number[], low: number[], close: number[]): Promise<any[]>;
- ultosc(high: number[], low: number[], close: number[], short: number, medium: number, long: number): Promise<any[]>;
- var(close: number[], period: number): Promise<any[]>;
- vhf(close: number[], period: number): Promise<any[]>;
- vidya(close: number[], short: number, long: number, alpha: number): Promise<any[]>;
- volatility(close: number[], period: number): Promise<any[]>;
- vosc(volume: number[], short: number, long: number): Promise<any[]>;
- vwma(close: number[], volume: number[], period: number): Promise<any[]>;
- wad(high: number[], low: number[], close: number[]): Promise<any[]>;
- wcprice(high: number[], low: number[], close: number[]): Promise<any[]>;
- wilders(close: number[], period: number): Promise<any[]>;
- willr(high: number[], low: number[], close: number[], period: number): Promise<any[]>;
- zlema(close: number[], period: number): Promise<any[]>;

