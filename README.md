# Predicting Stock Market Using Deep Learning

We gonna make stock market predictions based on past data

In order to achieve a great result, we will use the best available technologies and methods through Deep Learning models

<p float="left"> 
<img src="https://github.com/HudsonBarroso/stock-market-prediction/raw/main/images/tensorflow_logo.png" width="200">
<img src="https://github.com/HudsonBarroso/stock-market-prediction/raw/main/images/plotly_logo.png" width="200">
<img src="https://github.com/HudsonBarroso/stock-market-prediction/raw/main/images/yahoo_finance_Logo.png" width="200">
</p>

- 📚 **'Tensorflow official site'** - [link](https://www.tensorflow.org/)
- 📚 **'Plotly official site'** - [link](https://plotly.com//)
- 📚 **'Yahoo Finace API'** - [link](https://pypi.org/project/yfinance/)

## Dataset
The provided dataset is the stock market data from Yahoo!Ⓡ finance, using the API yfinance to download TESLA "TSLA"

## Steps to achieve the prediction

1. Scrapping the Stock Market data and Technical indicator data
2. Performing Data Processing on Time Series data
3. Creating and Training a LSTM Sequential Model on Tensorflow
  3.1 - LSTM with Bidirectional
  3.2 - Dropout
  3.3 - Callbacks: ModelCheckpoint, ReduceLROnPlateau
  3.4 - Optimizer: SGD


## Results
Previous Actual x Prediction

<img src="https://github.com/HudsonBarroso/stock-market-prediction/raw/main/images/tesla_result.png" width="600">

RMSE: 244.57

## Next Steps
1 - Get technical indicator data like: RSI AND EMA
2 - Model Deployment in AWS Sagemaker
