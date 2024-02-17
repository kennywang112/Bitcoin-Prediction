# Trading Bot Prediction and Strategy
## Abstract
1. This project is to build a trading bot example with **OKX api**, at the same time, I do analytics and preditions to a cryptocurrency and optimize our strategy.
2. Major work is to compare the profit between **long-term** model, **short-term** model, and our **own strategy**.
3. Model including Autoregressive Integrated Moving Average model(ARIMA), Prophet, Vector AutoRegressive(VAR), and Long Short-Term Memory(LSTM).
4. For model strategy, the predicted model will embed into the trading bot and give you best strategy.
5. Keep update...

## Ref
**OKX api**
- https://github.com/pyted
- https://www.okx.com/docs-v5/en/?python#order-book-trading-market-data-get-candlesticks

**ARIMA** Chinese:

- Formula : https://medium.com/@jason8410271027/%E6%99%82%E9%96%93%E5%BA%8F%E5%88%97%E5%88%86%E6%9E%901-arima%E5%9F%BA%E6%9C%AC%E7%90%86%E8%AB%96-%E5%AD%B8%E7%BF%92%E7%AD%86%E8%A8%98-25b88ef88ef

- Seasonal Variation : https://medium.com/@rofLin/%E8%A7%A3%E6%9E%90%E6%99%82%E9%96%93%E5%BA%8F%E5%88%97%E7%9A%84%E9%80%B1%E6%9C%9F%E6%80%A7%E8%AE%8A%E5%8B%95-seasonal-decomposition-8ced646fc26b

- Code : https://adaptable-haze-butterfly-551.medium.com/arima%E6%99%82%E9%96%93%E5%BA%8F%E5%88%97%E6%A8%A1%E5%9E%8Bpython%E6%87%89%E7%94%A8-%E9%8A%85%E5%83%B9%E6%A0%BC%E9%A0%90%E6%B8%AC-%E4%B8%80-4f91693e3ec6

**Prophet**

- Document : https://github.com/facebook/prophet
- Code : https://facebook.github.io/prophet/docs/quick_start.html#python-api
- Diagnostics : https://facebook.github.io/prophet/docs/diagnostics.html

**Vector Autoregression**

- Code:
https://www.statsmodels.org/dev/vector_ar.html

**File**

1. Useful_function: There are some useful function that will be use in **bot** file.
2. Bot: This is the main trading bot file.
3. Arima: This is for basic ARIMA model preparation, learning concept from this file and build **Arima_bot**.
4. Arima_bot: A trading bot combine with the knowledge of ARIMA result, then judge whether you can buy at this point.
