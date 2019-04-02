# easylanguage-tools
Easylanguage scripts and files relevant to program trading conducted on Multicharts/Tradestation. 
For a brief description of each item:

## Functions

- [Parabolic SAR](https://github.com/willbillionquant/easylanguage-tools/blob/master/functions/ZF_ParabolicSAR.txt): 
a rewrite of the parabolic SAR functions

## Indicators

-	[Ehlers](https://github.com/willbillionquant/easylanguage-tools/tree/master/indicators/Ehlers):
Some John Ehlers indicators, e.g. 
	-	[Stochastic RSI](https://github.com/willbillionquant/easylanguage-tools/blob/master/indicators/Ehlers/JE_StochRSI.txt)

-	[Equities](https://github.com/willbillionquant/easylanguage-tools/tree/master/indicators/Equities):
Indicators which applied most appropriately on daily or longer timeframe, such as
	-	[SCTR](https://github.com/willbillionquant/easylanguage-tools/blob/master/indicators/Equities/ZZ_SCTR.txt):
   Stockcharts Technical Rank indicator with slight modification
	-	[NumLogFromPeak](https://github.com/willbillionquant/easylanguage-tools/blob/master/indicators/Equities/ZZ_NumLogFromPeak.txt):
   Number of daily sigma from the peak price in a period (default 256 trading days/52 weeks)

-	[Oscillators](https://github.com/willbillionquant/easylanguage-tools/tree/master/indicators/Oscillators):
	-	[KDJ](https://github.com/willbillionquant/easylanguage-tools/blob/master/indicators/Oscillators/ZZ_KDJ.txt): extra J line from the stochastic oscillator.
	-	[ZScore](https://github.com/willbillionquant/easylanguage-tools/blob/master/indicators/Oscillators/ZZ_ZScore.txt): 
   Standard score in the context of Bollinger band, acting similarly as CCI (Commodity Channel Index).
   
-	[Price](https://github.com/willbillionquant/easylanguage-tools/tree/master/indicators/Price):
Plotting static or moving price levels on main chart, e.g.
	-	[KAMA](https://github.com/willbillionquant/easylanguage-tools/blob/master/indicators/Price/ZZ_KAMA.txt):
	Kaufman Adaptive Moving Average
	- 	[OpenCloseLines](https://github.com/willbillionquant/easylanguage-tools/blob/master/indicators/Price/ZZ_OpenCloseLines.txt):
	drawing horizontal lines of each day's opening price with prescribed opening and closing time.
	-	[Parabolic SAR](https://github.com/willbillionquant/easylanguage-tools/blob/master/indicators/ZZ_ParabolicSAR.txt):
	a rewrite of the parabolic SAR indicators (with plots)

-	[Timings](https://github.com/willbillionquant/easylanguage-tools/tree/master/indicators/Timings):
Plotting specific time, e.g.
	-	[1stfribar](https://github.com/willbillionquant/easylanguage-tools/blob/master/indicators/Timings/ZZ_1stfribar.txt):
	Plotting first Friday on daily chart. (usually the nonfarm payroll day)
	-	[3rdfribar](https://github.com/willbillionquant/easylanguage-tools/blob/master/indicators/Timings/ZZ_3rdfribar.txt):
	Plotting first Friday on daily chart. (usually the expiry day for US equities & futures monthly options)
	-	[HKRollTime] (https://github.com/willbillionquant/easylanguage-tools/blob/master/indicators/Timings/ZZ_HKRollTime.txt):
	Intraday timing for Hong Kong index futures rollover on the day prior to settlement day (2nd last working day in a month)

## Signals

- [LevRatio](https://github.com/willbillionquant/easylanguage-tools/tree/master/signals):
a template scheme of fixed leverage ratio compounding betting. My own detail expository can be found here:
[Evaluating the stable profitability of a Trading System through the Dilemma of Growth vs Drawdown](https://medium.com/@willbillionquant/%E8%A9%95%E4%BC%B0%E4%BA%A4%E6%98%93%E7%B3%BB%E7%B5%B1%E7%9A%84%E7%A9%A9%E5%AE%9A%E7%9B%88%E5%88%A9%E5%BA%A6-%E8%B3%87%E6%9C%AC%E9%AB%98%E9%80%9F%E5%A2%9E%E9%95%B7-vs-%E8%B3%87%E6%9C%AC%E5%9B%9E%E6%92%A4-730409f773f7)