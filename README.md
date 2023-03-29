# SP500_Predictions

This projecct starts off with scraping data using Yahoo Finance API. Initial predictions on the data provided resulted in a low precision score. There was room for improvement. I created new predictors which were rolling averages and the ratio between the rolling average and the close. This improved the precision score by 75%(from 0.325 to 0.569)! Main difficulty with this project was figuring out the right size n_estimators and min_samples_split so that we avoid overfitting. 
