# End to End Project - Bikes Assessment - Basic - Description

## Table of Content:
* [Overview](#Overview)
* [DataSet Features](#DataSet-Features)
*  [Languages and Libraries](#Languages-and-Libraries)
* [Technologies Used](#technologies-used) 

## Overview

### The objective of the project is - using historical usage patterns and weather data, forecast(predict) bike rental demand (number of bike users (‘cnt’)) on hourly basis.
### This dataset was provided by Hadi Fanaee Tork using data from [Capital Bikeshare](https://www.capitalbikeshare.com/system-data). We also thank the UCI machine learning repository for hosting the dataset.

## DataSet Features

### There are 17 features or instances in the Dataset and Below are the details of every feature.

1. instant: record index
2. dteday : date
3. season: season (1: springer, 2: summer, 3: fall, 4: winter)
4. yr: year (0: 2011, 1:2012)
5. mnth: month (1 to 12)
6. hr: hour (0 to 23)
7. holiday: whether the day is a holiday or not
8. weekday: day of the week
9. workingday: if day is neither weekend nor holiday is 1, otherwise is 0.
10. weathersit:
     1.  Clear, Few clouds, Partly cloudy, Partly cloudy
     2.  2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
     3.  3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
     4.  4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
11. temp: Normalized temperature in Celsius. The values are derived via (tt_min)/(t_maxt_min), t_min=*8, t_max=+39 (only in hourly scale)  
12. atemp: Normalized feeling temperature in Celsius. The values are derived via (tt_min)/(t_maxt_min), t_min=*16, t_max=+50 (only in hourly scale)
13. hum: Normalized humidity. The values are divided to 100 (max)
14. windspeed: Normalized wind speed. The values are divided to 67 (max)
15. casual: count of casual users
16. registered: count of registered users
17. cnt: count of total rental bikes including both casual and registered users

### The 'cnt' is the target variable for this problem

# Languages and Libraries

![Python 3](https://idroot.us/wp-content/uploads/2015/09/python-logo.jpg)
![Matplotlib](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTFVEhBrAKxWTGSXiJ7Cd9TsaM5kpKPVoPkXQ&usqp=CAUg)
![ScikitLearn](https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/200px-Scikit_learn_logo_small.svg.png)
![NumPy](https://static.javatpoint.com/tutorial/numpy/images/numpy-tutorial.png)
![Pandas](https://numfocus.org/wp-content/uploads/2016/07/pandas-logo-300.png)
