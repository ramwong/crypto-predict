# Crypto up/down Prediction
Testing crypto price will up or down tmr or a specific days later

# Dataset source:
- https://finance.yahoo.com/quote/ETH-USD/history/
- https://finance.yahoo.com/quote/BTC-USD/history/

# Period: 
1 to 3 years

# Algorithm
1. KNN
2. GaussianNB
3. RandomForest 

# Input: 
1. datasets : 1 to 3 years BTC-USD and ETH-USD dataset
    - put in the same folder with naming: 
            "1_year_BTC_USD.csv", "2_years_BTC_USD.csv", "3_years_BTC_USD.csv",
            "1_year_ETH_USD.csv", "2_years_ETH_USD.csv", "3_years_ETH_USD.csv"
2. day_to_predict : days to predict (e.g., 7 days after, it ups or downs?)
3. min_accepted_rate : between 0 and 1. 
    - it defines the minimal number of accepted cases rate
    - it affects the probability suggested to determine the prediction is really going to ups. (Which is the confidence)

# Output
best(most accurate in predict up) model, dataset and algorithm
