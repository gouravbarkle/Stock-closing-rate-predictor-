# Stock-closing-rate-predictor
Predict the closing rate of stock using stock market dataset features by Yahoo Finance.

# Dataset - Time Series data

Name- Yahoo Finance Nifty dataset
Source- Yahoo Finance
(https://in.finance.yahoo.com/quote/%5ENSEI/history/)

# Dataset Description
● 7 Attributes with 250 Rows.
● Attributes are as ‘Date’, ‘Open’, ‘Close’, ‘High’, ‘Low’, ‘Adj
  Close’, ‘Volume’.
● Attributes ‘Close’ act as label here i.e, Dependent variable.
● Remaining attributes are defined as features i.e, Independent
  variables.
● Time period : 22-Nov-2019 - 22-Nov-2020
● Frequency : Daily

# Data Preprocessing
● Importing the dataset into Pandas DataFrame format from .csv file.
● Splitting the dataset into the Training set and Test set using
  train_test_split.
● Taking care of missing data using SimpleImputer to fill ‘mean’ value to
  Null values.
● Feature Scaling the dataset values using StandardScaler to bring all
  into same scale

# Supervised learning 
Linear Regression is used as Supervised learning method to
predict the label i.e, ‘Close’ value of a stock using various attributes
like ‘Date’, ‘Open’, ‘High’, ‘Low’, ‘Adj Close’, ‘Volume’ as features to
the Regression model.
