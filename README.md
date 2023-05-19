# Weather Forecasting App

### Introduction

Ever wondered what the weather holds for your current location? The Weather app has you covered! Discover atmospheric pressure, conditions, visibility, humidity, precipitation, dew point, wind speed, direction, plus a 10-day future forecast and hourly updates. 
Intriguing!

### Work Process

Firstly, I to used a weather API for fetching the data from the Open Weather Map website by generating an API keyof Current Weather Data (that has an access of current weather data for any location on Earth including over 200,000 cities), and then created a configuration file to store the key. Finally, I used that configuration file in the python script for Forecasting GUI App.

Also I used ttk module for styling my app UI and PIL Module to add weather icon into the upgraded version of my app as shown below.

### Tool Used

* Python

Modules required:
1. Tkinter: It is a built-in python library for making GUI using tkinter toolkit.
2. Requests: It is a library which helps in fetching the data with the help of URL.
3. PIL: Python Imaging Library is a free and open-source additional library for the Python programming language that adds support for opening, manipulating, and saving many different image file formats.
4. ttkbootstrap: This module provides access to the Tk themed widget set.

### Weather Forecasting App ScreenShots

![Screenshot 2023-05-01 182051](https://user-images.githubusercontent.com/84131752/235453977-f4b0fe49-f4e7-4024-ae44-4616ffd6a1d3.png)

#### Upgraded App Screenshot

![Screenshot 2023-05-11 124449](https://github.com/nikitaprasad21/Weather-Forecasting-App/assets/84131752/232a0c3c-8db1-4de7-8db2-a58c92421540)

#### Upgraded App 2.0 Screenshot

![Screenshot 2023-05-20 014620](https://github.com/nikitaprasad21/Weather-Forecasting-App/assets/84131752/b66ac159-fcd5-4b23-bce3-a4b9ade790b8)


##### Note:
Steps to create the Configuration file:
1. Create a text file named "waether_key"on your jupyter notebook.
2. Write key name enclosed in closed brackets in it as [api].
3. Create a variable key here I used was "key" and paste the key you copied from the Open Weather Map website.
