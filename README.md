# Predict Future Sales
The dataset consists of time-series data of daily sales provided by the Russian software firm 1C Company. 
The goal is to predict total sales for a number of products in various stores in Russia during one month.

In 1_data_prep we clean the data and perform feature engineering.

In 2_xgb_model we implement an XGBoost model and try various methods to improve it.

Finally, in 3_lgb_model we implement a LightGBM model which gives us a position on the public leaderboard that puts us in the top 6%.
