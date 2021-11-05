# Used Cars: Data Analysis and Price Prediction

The price of used cars in Brazil varies quite a lot, even though there is a government table (FIPE) that suggestably bounds prices within a range. We used a car sellers dataset to distinguish which factors were most important in defining the price range.

[The complete notebook can be seen here](https://github.com/pedroafleite/used_cars/blob/main/car_data.ipynb) *(in Portuguese.)*

In this project, it was performed:
- Exploratory Data Analysis
  - Bivariate analysis
  - Multivariate analysis
  - Correlation heat
- Data preparation
  - Dealing with categorical data with one-hot encoding
  - Dealing with outliers, null values and infinite values
  - Defining target variable
  - Dealing with asymmetry using:
    - Logaritimic transformation
    - Box-Cox transformation
- Data modelling (Regression):
  - Lasso
  - Elastic Net 
  - Stochastic Gradient Descent
  - XGBoost
  - Light GBM
