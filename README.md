# Correlation-based algorithmic trading applied to crypto markets

This repository contains the bachelor thesis about `Correlation-based algorithmic trading applied to crypto markets` by Leonhard Esterbauer and the related experiments. The day data contains day-closing prices for investigations over longer periods and trades data contains all single trades of different exchanges to investigate the price changes in smaller intervals. The results are calculated in a juypter notebook.

### Datasources used in this repository:
- Day data:
  - [Coingecko](https://www.coingecko.com)
- Trades data:
  - [Bitfinex](https://www.bitfinex.com)
  - [Kraken](https://www.kraken.com)

## Abstract
Over the last years, the price development of cryptocurrency markets encountered noticeable ups and downs. It looks like the dominance of a few big crypto assets like Bitcoin, Ethereum and Litecoin determine the markets and run ahead less popular currencies that behave similarly. In this work, a correlation analysis of major crypto assets is done and dependencies in price developments are searched. For this purpose, data from online sources are collected and compared using statisti- cal measurements. Furthermore, lead-lag properties are investigated and approaches for using the gathered results in an algorithmic trading scenario are given. To get an overview of the presented approaches, performance measurements show the profitability over a selected timespan compared to approaches neglecting correlation values. The results show a high correlated crypto market with small groups of higher correlated assets. Moreover, no relevant lead-lag relationships can be iden- tified in the selected asset combinations which refute the starting thesis that a few leading assets determine the market. Even if some assets look promising and show a higher correlation when compared to a forward shifted signal, the high correlation values are also measured when the same assets are compared to the signal shifted backward. For this reason, the lead-lag investigation does not provide significant values or clear indicators for a real trading scenario. An additional real- world trading simulation with promising signals supports this thesis. The simulation uses common trading approaches with an extension of correlation and lead-lag calculations and comes to the re- sult that none of the presented approaches can outperform a traditional trading approaches with greedy analysis. Moreover, the presented approaches exhibit similar or even worse profits when simulated on historical data using backtesting. As only less research about price development of crypto markets exists, this work acts as an overview of cryptocurrencies and their correlation values and additional investigations are necessary to rate and classify the gathered results.

### Keywords
correlation, trading, cryptocurrencies, crypto markets, lead-lag, algorithmic trading
