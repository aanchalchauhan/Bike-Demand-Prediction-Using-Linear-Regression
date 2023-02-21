# Bike-Demand-Prediction-Using-Linear-Regression

This model is designed to predict the demand for bike rentals based on various features such as season, weather, and time of day.

# Requirements :
Python 
NumPy
Pandas
Scikit-learn

# Dataset
The model is trained on the Bike Sharing Dataset. 
The dataset includes hourly bike rental data for the Capital Bikeshare program in Washington, D.C. for two years (2018-2019). 
The dataset consists of 730 instances and 16 features.

# Features
The features used in the model are:

season (1:spring, 2:summer, 3:fall, 4:winter)
weekday (0 to 6)
workingday (1:yes, 0:no)
weathersit (1:clear, 2:mist/cloudy, 3:light snow/rain, 4:heavy rain/snow)
temp (normalized temperature in Celsius)
humidity (normalized humidity)
windspeed (normalized wind speed)
year (2018-2019)
month (1 to 12)
count (count of bikes)

# Model
The model is a simple linear regression model that uses the above features to predict the bike rental demand. 
The model is implemented using Scikit-learn's LinearRegression class. The model is trained on 70% of the data and tested on the remaining 30%.

# Usage
To use the model, simply download the Bike Demand Prediction using Linear Regression.ipynb file and open it in Jupyter Notebook or a compatible program. 
You can modify the code and input your own data to make predictions.


# Author
This project was created by Aanchal Singh Chauhan. For more information, please contact www.linkedin.com/in/aanchalschauhan

