# Project: DS Applications in Finance

## Description of the project
The project's main focus is on implementing the most accurate and profitable trading strategies and automating the process of trading. In this project we would be using Bitcoin cryptocurrency as it is known for its volatility in the market. Trading strategies that were used in the project are also built upon volatility and short- or long-term trend measurements

## Bibliography
1. Investopedia https://www.investopedia.com
2. RBC Journal (РБК) https://www.rbc.ru
3. Technical Analysis Library in Python https://technical-analysis-library-in-python.readthedocs.io/en/latest/index.html
4. GitHub https://github.com
5. Livermore –– "How to trade in stocks" (pdf) https://www.trendfollowing.com/pdfs/Jesse_Livermore-How_To_Trade_In_Stocks_(1940_original)-EN.pdf
6. Steve Nison –– Japanese Candlestick (pdf) https://dl.kohanfx.com/pdf/stevie-nison-candlestick-(KohanFx.com).pdf
7. Algorithmic Trading with Python (YouTube) https://www.youtube.com/playlist?list=PLwEOixRFAUxZmM26EYI1uYtJG39HDW1zm
8. ML-Quantitative Finance https://www.ml-quant.com


## Stack
**`pandas` `numpy` `sklearn` `pandas_ta` `ta` `binance`**

## Methods and Models
**`LogisticRegression` `RandomForestClassifier` `GradientBoostingClassifier` `Upsampling` `Downsampling` `Scaling` `AUC_ROC` `F1`**

## Plan
1. Get access to binance account
2. Upload data on a 5-minute timeframe
3. Calculate trading strategies (RSI, Stochastic Oscillator, MACD, Bollinger Bands, Keltner Channel)
4. For each strategy calculate percentage of calls for the whole dataframe (call is "1" – buy the stock)
5. Calculate percentage of true calls (it is common that trading strategies are wrong time to time)
6. Check combinations of the most profitable strategies
7. Train the model based on the results from part 5) and 6)
8. Obtain the model that predicts the truthfullness of a call for a particular trading strategy

