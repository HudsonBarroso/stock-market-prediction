# Predicting Stock Market Using Deep Learning

We gonna make stock market predictions based on past data

In order to achieve a great result, we will use the best available technologies and methods through Deep Learning models

<img src="https://github.com/HudsonBarroso/stock-market-prediction/raw/main/images/tensorflow_logo.png" width="390" align="right">

---

## Dataset
The provided dataset is the stock market data from Yahoo!Ⓡ finance, using the API yfinance

## Steps to achieve the prediction

1. Scrapping the Stock Market data and Technical indicator data
2. Performing Data Processing on Time Series data
3. Creating and Training a LSTM Sequential Model on Tensorflow

## Hyperparameter Tuning
I choosed the pretrained model ResNet-18, it has been trained on a subset of the ImageNet database. The model is trained on more than a million images, and can classify images into 1000 object categories

Hyperparameter Tuning Job
![Hyperparameter Tuning Job](hp_tunning.PNG?raw=true? "Hyperparameter Tuning Job")

Hyperparameter Tuning Metrics
![Hyperparameter Tuning Metrics](hp_tunning_log_metrics.png?raw=true "Hyperparameter Tuning Metrics")

Training Job Output
![Training Job Output](training_result_v2.png?raw=true "Training Job Output")

### Results
On going


## Model Deployment
Thee Model Deployment gonna be developed in AWS Sagemaker
