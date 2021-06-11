# Project_2
By John Kelly, Sean Brennan, Quinn Luong, and Priscilla Wong
## Hypothesis:
### Which machine learning model best forecasts stock prices?

## Data and parameters:
### Data: We decided to use Yfinance as our primary source for pricing data because they have consistent daily close prices which will be our data points.
### Model training: We decided to use 70/30 training to testing data
### Model Performance Evaluation: Graph visuals of the three respective models to decide which predictor follows the actual prices most closely
### Variables: To test the theory that a volatility expectation index can predict the price of a stock or stock index, we used the VIX index as a predictor of the Russell 2000 index. We also decided to test this to forecast the price of an individual stock, BRK-B (Berkshire Hathaway Class B shares)

## Model 1: LSTM Using VIX (volatility index) as a predictor of RUT (Russell 2000)'s prices:
### LSTM Models are a great tool for time series forecasting. Since we have used LSTM in the context of predicting securities prices in this class, we decided to structure our models based on our prior class activities and homework. Throughout all our models, we are using 2 years of prices (from January 2019 through the end of May 2021). Our window size is 10 (for 10 trading days). Using multiples of 10 will allow us to run our models faster. We had considered using a window size of 1 for more accurate data but that would take a long time to run.
### Discovery: We found that this model

## Model 2: LSTM Using historical prices of RUT (Russell 2000) as a predictor of it's future prices
### Discovery: 

## Model 3: Holt-Winters model using exponential smoothing and seasonality aspects to use VIX as a predictor of RUT's future prices
### Discovery:
