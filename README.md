﻿# GoogleStockPrice

## Description
This project aims to predict upward and downward trends in Google stock prices using a Long Short-Term Memory (LSTM) model.

Leveraging a five-year dataset of Google stock prices from 2012 to 2016, we will train the LSTM to capture and correlate trends in the stock price. 

Ultimately, the model will be utilized to forecast the price trend for January 2017 based on the learned patterns and correlations from the training data.


## Dataset
This dataset provides historical stock price information for Google. The data is sourced from [Kaggle](https://www.kaggle.com/datasets/vaibhavsxn/google-stock-prices-training-and-test-data) and spans from the beginning of 2012 to the end of 2016. 

The dataset includes the following attributes:
- ``Date``: The specific date corresponding to the stock price data.
- ``Open``: The opening price of Google stock on that particular date.
- ``High``: The highest price of Google stock reached during the trading day.
- ``Low``: The lowest price of Google stock reached during the trading day.
- ``Close``: The closing price of Google stock on that particular date.
- ``Volume``: The total number of shares of Google stock traded on that day.

## Setup the Project

0. Ensure you have Python installed on your system. 

1. Clone the repository:
    ```bash
    git clone git@github.com:Antoine-ValentinCharpentier/GoogleStockPrice.git
    cd GoogleStockPrice
    ```
2. Initialise the venv:
    ```bash
    python -m venv .venv
    .venv\Scripts\activate OU source .venv/bin/activate
    pip install -r requirements.txt
    ```

3. Execute the script ``rnn.ipynb``
