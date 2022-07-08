# Group Project 2

![presentation_gif](./images/project_gif.gif)

## Table of Contents

1. Hypothesis
2. Data Collection and Clenaing
3. Choices for models & Perfromance
4. Contributions

## Hypothesis

- We use machine learning tools to predict the price of ethereum from historical data, economic indicators, and community sentiment on ethereum specifically from twitter.
- We test this hypothesis by building LSTM and GRU models

## Data Collection & Cleaning

- Our Sources were: 
    - [Twint Protocol](https://github.com/twintproject/twint) for Collecting tweet data 
    - [OWlracle API](https://owlracle.info/eth) for collecting Gas price history 
    - [Kaggle](https://www.kaggle.com/datasets/varpit94/ethereum-data) for ETH to USD Historical Data 
    - FRED for personal savings percentage data 
    - Market Watch for S&P 500 historical data

## Choices for models & Performance scores

- We used two models to predict the price of ethereum
    - Long Short-Term Memory (LSTM) model from keras
    - Gated Recurrent Unit (GRU) model form keras

- Spliting our data to train and test 

![GRU Model Peerformance](./images/train_test_split.png)

- LSTM vs GRU model perfromances
    - LSTM evaluation had 8.98% loss, 91% accuracy 
    ![LSTM Model Peerformance](./images/lstm_prediction.png)

    - GRU evaluation had 10.65% loss, 89.35% accuracy
    ![GRU Model Peerformance](./images/gru_prediction.png)

## Contributions

- [Meek Msaki](https://github.com/mmsaki)
    - Get historical gas prices and clean data.
    - Set up and run LSTM model

- [Kyle Plathe](https://github.com/kyleplathe)
    - Get historical eth prices and clean data
    - Get S&P 500 historical
    - Get US savings historical data
    - Set up GRU model 

- [Richard Melvin](https://github.com/rgmelvin)
    - Get historical sentiment for ethereum 2017 - 2020
    - Twitter api sentiment analysis with nltk and vader
    - Perfromed PCA analysis


## Presentation & Files

**Files:** 
- [Gas price data collection](./eth_gas_price_history_data_collection.ipynb)

- [Twint Protocal data collection](./Twint_protocol_2.ipynb)

- [Eth data cleanup](./Eth%20Data%20Cleanup.ipynb)

- [Sentiment Analysis](./Sentiment.ipynb)

- [LSTM Model price predictions](./lstm_for_eth_price_prediction.ipynb)

- [GRU Model price predictions](./ETH%20GRU%20Prediction.ipynb)

- [Project Presentation](./group_project_2_presentation.pdf)


