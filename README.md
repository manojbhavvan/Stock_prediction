# INDIAN STOCK MARKET PREDICTION USING LSTM AND BILSTM MODELS
## Abstract 
Stock prediction is a challenging problem due to the complexity and volatility of financial markets. Recurrent neural networks (RNNs) have been used for stock prediction, and Long Short-Term Memory (LSTM) and Bidirectional LSTM (BiLSTM) models have shown promising results. In this paper, we present an abstract of a study that investigates the use of LSTM and BiLSTM models for stock prediction. We trained LSTM and BiLSTM models on historical stock price data and other relevant factors & sentiment analysis. The trained models were used to predict future stock prices. We evaluated the performance of the models using various metrics and compared them to traditional machine learning models. Our results show that LSTM and BiLSTM models outperform traditional machine learning models for stock prediction. The use of LSTM and BiLSTM models allows capturing temporal dependencies in the input data and learning complex patterns, leading to more accurate predictions. However, there are also limitations to using these models, such as the difficulty of obtaining accurate and relevant data for training and the models’ inability to predict sudden changes in the stock market. This study provides insights into the use of LSTM and BiLSTM models for stock prediction and highlights the potential benefits and challenges of using these models.

## Work done
We got the results in python notebook. But since the stock prices vary and each day a model dominates another the result won't be stable on prediction. But BILSTM has trained and has a good score than LSTM model which was dominant. To calculate the score, we have used RMSE(Root Mean Square Error). The error ratio which resulted was

LSTM: 62.76722252172304
BILSTM: 63.810619383806355

## Team Members
1. Manoj Bhavvan B
2. Kalaiyarasan M 
3. Abdul Vajith M
4. Arun Kumar M

## Libraries Used
1. Tiingo - Fetch stock market data
2. Matplotlib - Representation of data in graphs
3. Numpy - Data Manipulation
4. Sklearn - Preprocessing of Data
5. Tensorflow - Build LSTM and BILSTM model

## Future Work
Deploy as a Full Stack Web Application which can give suggestions of multiple stocks.
