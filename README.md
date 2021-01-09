# Data-Mining-Regression-Analysis
#### StockX-2019 Data Contest
**Yeezy & OFF-WHITE Sales Price Prediction**
* [Presentation](https://github.com/dss-14th/reg-repo-5/files/5790222/X_stock_reg.pdf)
* In this project, we downloaded a dataset that is about Luxuary Shoes transaction of online platform(StockX). 
  Then, we made derived variable from the dataset and split our data into training and test sets and scaled for data modeling.
  Evaluate our model using RMSE of test dataset, and finally we use model to predict sales price of new model. 
  
  
* team : 김희주, 이원진, 정성용

### Data : StockX-Data-Contest-2019-3.csv
We've downloaded a StockX transaction dataset, which contains Yeezy and Off-white sales price, price date, design, etc.

* Data Source : [StockX-dataset](https://www.kaggle.com/hudsonstuck/stockx-data-contest)

### Preprocessing and EDA
  * Made derived variable for regression modeling (date_diff, price_ratio,etc)
  * Added design variable of Yeezy (handle, color,lettering, etc)
  * Removed missing value, outlier(Upperfence of IQR 2.0)


### We modeled:
  * LinearRegression model
  * OLS model
  * DecisionTreeRegressor model
  * RandomForestRegressor model
  * GradientBoostingRegressor model
  * XGBRegressor model

### Sales Price Prediction
Predict Sales price of YEEZY and Off-white using our final model(XGBRegressor model)

     * Yeezy Israfil
       Release date: 2020.08.22
       Price: $220 USD
      
     * Nike Zoom Terra Kiger 5 Off-White White (W) 
       Release date: 2019.06.24
       Price : $180 USD


### Result
Most effective variable for Resale price of shoes is 'handle trimming' in Yeezy and Zoom model in Off-white.


    








