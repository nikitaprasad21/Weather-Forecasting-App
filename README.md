# Weather Forecasting App

### Introduction

The Weather app is use to check the weather for your current location. The weather app also provides atmospheric pressure, weather conditions, visibility distance, relative humidity, precipitation in different unites, dew point, wind speed and direction, in addition to ten days in future and hourly weather forecast.

### Work Process

Firstly, I to used a weather API for fetching the data from the Open Weather Map website by generating an API keyof Current Weather Data (that has an access of current weather data for any location on Earth including over 200,000 cities), and then created a configuration file to store the key. Finally, I used that configuration file in the python script for Forecasting GUI App.

### Tool Used

* Python

Modules required:
1. Tkinter: It is a built-in python library for making GUI using tkinter toolkit.
2. Requests: It is a library which helps in fetching the data with the help of URL.

### Weather Forecasting App ScreenShot

![Screenshot 2023-05-01 182051](https://user-images.githubusercontent.com/84131752/235453977-f4b0fe49-f4e7-4024-ae44-4616ffd6a1d3.png)

Upgraded App Screenshot

![Screenshot 2023-05-11 124449](https://github.com/nikitaprasad21/Weather-Forecasting-App/assets/84131752/232a0c3c-8db1-4de7-8db2-a58c92421540)

##### Note:
Steps to create the Configuration file:
1. Create a text file named "waether_key"on your jupyter notebook.
2. Write key name enclosed in closed brackets in it as [api].
3. Create a variable key here I used was "key" and paste the key you copied from the Open Weather Map website.
