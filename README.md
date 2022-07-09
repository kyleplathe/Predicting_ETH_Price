# Meek Updates

## Updates

- Resources used:
    - [x] [crypto_exploits.csv](./resources/crypto_exploits.csv)
        - **Source:** [CryptoSec](https://cryptosec.info/defi-hacks/)
    - [x] [Eth Gas prices.csv](./resources/eth_gas_prices.csv)
        - **Source:** [OWlracle API](https://owlracle.info/eth)
    - [x] [ETH-USD Hisorical prices.csv](./resources/ETH-USD.csv)
        - **Source:** [Kaggle](https://www.kaggle.com/datasets/varpit94/ethereum-data)

## Conclusions 

Data cleaning was done when collecting gas price historical data fro owracle. I am really thankful that owracle was able to provide me with historial data from 2017 just overnight after requestin it on telegram chat. 
    
- [Eth Gas prices data collection notebook](./eth_gas_price_history_data_collection.ipynb)

Finally after gathering all the dat I needed fro my machine learnign models I trained and run the model. The results can be seen in the following notebook:
    
- [Long Short-Term Memory model notebook](./lstm_for_eth_price_prediction.ipynb)

### Model evaluation

- Lstm model had a 8.98% loss, a 91% accuracy
![](./images/lstm_prediction.png)

## Checklist

- [x] Selected all Models to use and compare. 
    - LSTM model
    - GRU Model

- [x] Use Colab Notebook with analysis
- [x] Add price prediction with GRU model
- [x] Add price prediction with LSTM model
- [x] Process crypto exploits historical data with amount loss 
- [x] Add Presentaion 
- [x] Update Readme

## Improvements

- Possibly collect market cap data from crypto market. Due to time running out to submit this project I didn't have the opportunity and time to explore effects on market cap on the price of ethereum although I have a feeling it could be useful. Also I suspect the occurences of cryptocurrency thefts and exploits could be affecting price movements due to possible shifts in the sentiment around cryptocurrency users. However, this is a speculation that can tested when we use the historical data on exploits on blockchain companies.