# Apple-Stock-Price-Prediction
 
## Three Different Models to Predict the Price of the Apple Stock (Regression)

Model 1: 2 Hidden layers (128 and 64 Neurons), 2 Dense Layers, 1 epoch with whole batch set <br/>

Model 2: 2 Hidden layers (128 and 64 Neurons), 1 Dense Layers, 0.2 dropout rate, 50 epochs with 64 size batch set <br/>

Model 3: 3 Hidden layers (128, 64, and 64 Neurons), 1 Dense Layers, 0.2 dropout rate, 50 epochs with 64 size batch set <br/>

## Installation Guide

### Please update the following parameters to get the latest prediction on the specific model <br/>
### data = yf.download('AAPL','2008-01-01',<TO_LATEST_DATE>) <br/>
### new_data = yf.download('AAPL', <FROM_LATEST_DATE>) <br/> 

This will allow the model to update the parameters and try to predict the price of the stock for the next 30 days. <br/>


1) Download the "Explore_the_Data.ipynb
 Allow to explore the data
 
 2) Download Model_1 Folder and Run all
  Model 1 output will be shown and a table at the end to sell/buy/hold the stock
  
 3) Download Model_2 Folder and Run all
  Model 2 output will be shown and a table at the end to sell/buy/hold the stock
  
 4) Download Model_3 Folder and Run all
  Model 3 output will be shown and a table at the end to sell/buy/hold the stock
