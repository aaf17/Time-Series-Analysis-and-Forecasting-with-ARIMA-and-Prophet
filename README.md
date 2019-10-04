# Time Series Analysis and Forecasting with ARIMA and Prophet

This project is focused on the Brent oil price dataset to analyze the prices of oil with respect to time
and predict the future prices using the Time Series Forecasting models like ARIMA and Prophet. Experiments and results are presented and a comparison is done to compare the actual prices with the predicted prices and also to compare the performance of both the models on the same dataset in order to find the most accurate forecasting model.

### Prerequisites

Make sure you have Python 3 and Anaconda installed.

## Getting Started

  Install the Python libraries and packages using pip command:

    
    $pip install numpy

    $pip install Pandas

    $pip install matplotlib

    $pip install seaborn

    $pip install statsmodels

    $pip install fbprophet

    

### Data Preprocessing

```
cleanData.ipynb                      

```

The file cleanData.ipynb contains all the data preprocessing steps such as removing the unwanted rows/columns, giving appropriate names to columns, check for missing and null value, etc. It also converts the original xls file to csv format.
After the data is cleaned a new csv file is generated that contains clean data named clean_data.csv

### Data Visualization

```
data_plot.ipynb                      

```

Using Python's plotting libraries Matplotlib and Seaborn, a simple line plot and a heat map has been generated to get a high level statistical overview of the data.

### Forecasting with ARIMA Model

```
ARIMA.ipynb                      

```

Statsmodel package has been used to implement ARIMA model. The model implementation has been done step by step such as data decomposition, conversion to a stationary time series, ACF and PACF plots. The best model is selected based on lowest AIC / BIC value. Prediction and forecasting is done using the selected model.

### Forecasting with Prophet Model

```
Prophet.ipynb                      

```

Prophet model has been implemented using fbprophet package from Facebook. Prediction and forecasting is made and the performance of the model is evaluated using cross validation from prophet.diagnostics. 
    Accuracy metrics have been identified such as rmse.

##  Contributor

    Aafia Jabeen

    Supervisor: Dr. Ting Hu

