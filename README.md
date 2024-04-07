# Bitcoin-Prediction
 Bitcoin forecast for the next month compared to the last 4 years.

### Source
Bitcoin Prediction: https://www.investing.com/crypto/bitcoin/historical-data

The data goes from 2021-03-01 to 2024-02-29. The purpose of this project is to forecast the daily price of bitcoin (BTC/USD) for the next month based on the last 4 years using LSTM and GRU models.

### Analysis
An initial analysis of financial data relating to bitcoin was carried out. After that, the price time series was analyzed over time. The LSTM and GRU models were built with the same characteristics to predict the data. A bootstrap resampling technique was performed to establish the confidence interval for both models. At the end, model predictions are compared against real data.

### Results

![bitcoin_predict](https://github.com/aryelsoares/Bitcoin-Prediction/assets/165218194/63b2016c-b140-4a9a-88b3-ac11aef221ce)

For the hyperparameters and layers used in building the models, the best model in this case is LSTM. You can see that all real data was captured by the LSTM confidence interval, unlike GRU which captured partially. Both models indicated a growth trend over time following the behavior of real data overall.

### Note
This project serves to give a basis on how to predict the bitcoin daily price trend for a month using LSTM and GRU models. It's important to take a more detailed look at deep learning models if you want to invest in cryptocurrencies. The best model varies according to the behavior of the data, including other scenarios such as adding predictor variables, changing layers and so on.