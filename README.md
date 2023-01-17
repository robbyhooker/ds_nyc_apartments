# NYC Real Estate Sales Price Estimator: Project Overview
* Created tool that estimates NYC real estate sale prices to help someone decide if they are getting a fair price, or to help someone generate a price
* Cleaned data to make it more sensical and to create new features (i.e. building age)
* Optimized Random Forest Regressor with GridSearchCV to obtain a good model 
* Produztionized model by building API

## Recources 
**Python Version**: 3.8.5
**Packages Utilized**: pandas, sklearn, numpy, matplotlib, seaborn, flask, pickle
**IDE's**: Jupyter Notebook, Spyder
**Flask API Tutorial Article**: https://towardsdatascience.com/productionize-a-machine-learning-model-with-flask-and-heroku-8201260503d2
**Data Set and Info**: https://www.kaggle.com/datasets/new-york-city/nyc-property-sales

## Data Cleaning
* Removed nonsense and unnecessary columns (EASE-MENT, ADDERSS, etc.)
* Removed missing value columns from sale price, land, and gross square feet
* Removed time stamp from date column and engineered month sold feature
* Cleaned sale price column using quantile outliers
