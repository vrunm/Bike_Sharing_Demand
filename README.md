# Bike Sharing Demand
We train a model to predict the number of bike rentals at any hour of the year given the weather conditions. The data set was obtained from the Capital Bikeshare program in Washington, D.C. which contained the historical bike usage pattern with weather data spanning two years

A SHORT DESCRIPTION OF THE FEATURES:
datetime - hourly date + timestamp  

season -  1 = spring, 2 = summer, 3 = fall, 4 = winter 

holiday - whether the day is considered a holiday

workingday - whether the day is neither a weekend nor holiday

weather -

1: Clear, Few clouds, Partly cloudy, Partly cloudy 

2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist 

3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds 

4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog 

temp - temperature in Celsius


humidity - relative humidity

windspeed - wind speed

casual - number of non-registered user rentals initiated

registered - number of registered user rentals initiated

count - number of total rentals

Results from the Exploratory Data Analysis:
1.During Summer the most rides are taken
2.The highest demand for bikes is from 7-10am and 3-7pm these being the office times for most metro cities
3.The highest dmeand for bikes is when the temperature range is in between 30-35

Results from Regression Analysis:
Different Regressors are used on the models:
1.BaggingRegressor
2.AdaBoostRegressor
3.RandomForestRegressor
4.KNeighborsRegressor

Comparing the MSE values for the different models
It can be seen that the Random Forest Model performs the best. It does not suffer from overfitting


