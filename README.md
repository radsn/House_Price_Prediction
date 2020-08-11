# House Price Prediction
Predict house prices in Ames, Iowa using various machine learning models

#### Project Flow: 
-Import Libraries and Read Data
-Look at each column in the training data - understand its purpose and importance
-Expectation: What is my expectation about the variable influence on the 'SalePrice'
-Separate into numerical and categorical variables
-Data Visualization of Numerical variables as Scatterplots
-Data Visualization of Categorical variables as Boxplots
-Heatmaps -- find multicollinearity
-top10 Heatmap - highly correlated with 'SalePrice' - remove multicollinear variables
-Combine Train and Test
-Handle Missingness
-Target ('SalePrice') Analysis and log-Transformation
-Feature Engineer (generate new features)
-Dummify
-Split back into Train and Test and Export Data into csv files
-Model Testing And Running: Lasso, Ridge, ElasticNet, XGBoost, Huber
-Prediction
