# Stock-Price-Predictor-using-LSTM
Stock Price Prediction using Deep Learning(LSTM model)

A stock market, equity market, or share market is the aggregation of buyers and sellers of stocks (also called shares), which represent ownership claims on businesses. Stock market prediction is the act of trying to determine the future value of a company stock or other financial instrument traded on an exchange. The successful prediction of a stock's future price could yield significant profit. The efficient-market hypothesis suggests that stock prices reflect all currently available information and any price changes that are not based on newly revealed information thus are inherently unpredictable. Others disagree and those with this viewpoint possess myriad methods and technologies which purportedly allow them to gain future price information. Accurate prediction of stock market returns is a very challenging task due to volatile and non-linear nature of the financial stock markets. With the introduction of artificial intelligence and increased computational capabilities, programmed methods of prediction have proved to be more efficient in predicting stock prices. In this work, Artificial Neural Network and Random Forest techniques have been utilized for predicting the next day closing price for companies belonging to different sectors of operation. As part prediction model, historical prices are combined with sentiments and then trends are predicted. The financial data: Open, High, Low and Close prices of stock are used for creating new variables which are used as inputs to the model. The models are evaluated using standard strategic indicators: RMSE and MAPE. The low values of these two indicators show that the models are efficient in predicting stock closing price.


Created a LSTM model to predict the stock prices of SBI using hostorical data.
Predicted open prices for next month.

Generated calls on the stock using simple trading strategies:

When the 7MA crosses above the 14MA, it's aBUY signal, as it indicates that the trend is shifting up. This is known as a "golden cross."

When the 7MA crosses below the 14 MA, it's a SELL signal, as it indicates that the trend is shifting down. This is known as a "dead/death cross."
