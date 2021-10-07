# Cryptocurrency-Closing-Price-Prediction

This solution allowed me to take 2nd place in the Cryptocurrency Closing Price Prediction Hackathon and 4th place in the Cryptocurrency Closing Price Prediction Competition.

I would Like to Thank Zindi team and Think-it Company who organized this competition. It was extremely interesting Topic.

# Competition Goal

The goal of this project is to predict future cryptocurrency prices using the trading time series of a cryptocurrency’s price, in addition to a set of qualitative features (news, social impact, Twitter, Reddit, social media sentiment analysis).

# Approach

The main thing in the solution: filling nan values with -1, Scaling our data using the famous RobustScaler function from Sklearn then Stacking several model(Ridge,LinearRegression,BayesianOptimizer,ExtraTreeRegressor,GradientBoostingRegressor,RandomForestRegressor,XGBRegressor) using a final estimator a baggingregreesor of 15 LinearRegression model
