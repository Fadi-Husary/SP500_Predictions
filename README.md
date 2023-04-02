# SP500_Predictions

This project starts off with scraping data using Yahoo Finance API. Initial predictions on the data provided resulted in a low precision score. There was room for improvement. I created new predictors which were rolling averages and the ratio between the rolling average and the close. This improved the precision score by 75%(from 0.325 to 0.569)! Main difficulty with this project was figuring out the right size n_estimators and min_samples_split so that we avoid overfitting. 

#### Steps:
- Scrape data from Yahoo Finance.
- Clean and analyze the data.
- splitting data, training a model, and making predictions.
- evaluating accuaracy of those predictions.

## Packages
#### To follow this project you will need:
- Python
- Python packages:
  - pandas
  - yf (Yahoo Finance API)
  - RandomForestClassifer from sklearn
  - precison_score from sklearn

## Data
The data for this project used data on the ticker $GSPC, which was scraped from [here](https://finance.yahoo.com/quote/%5EGSPC/)
