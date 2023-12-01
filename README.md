# Crypto Oversampling Prediction Model

## Description:
- This model aims to stack many crypto currency historical data as well as other correlated assets such as Gold, who have longer histories, and train a prediction model on them.
- It utilizes yfinance, pandas, xgboost, scipy, matplotlib and seaborn to find correlated assets and stack them on top of each other to give the model more data to be exposed to due to the target asset (BTC) not having a long history to draw from.
