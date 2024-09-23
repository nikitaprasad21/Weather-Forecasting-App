# Weather Forecasting App

## Project Background
The Weather Forecasting App is designed to provide real-time weather information for any location worldwide using data sourced from the **Open Weather Map API**. The app enables users to view various weather parameters such as temperature, wind speed, humidity, atmospheric pressure, and more. The app was developed using **Python**, leveraging **Tkinter** library to create a user-friendly graphical interface for seamless weather updates. This project is aimed at enhancing user convenience by providing accurate weather forecasts for informed planning and decision-making.

## Dataset Structure
The dataset is dynamically fetched from the **Open Weather Map API** in **JSON** format. The following key information is extracted and displayed in the app:

![image](https://github.com/user-attachments/assets/739f821e-4c5d-4460-b7f1-22c64a93ee80)

## Executive Summary
The Weather Forecasting App utilizes data from the Open Weather Map API to provide detailed and real-time weather updates, including temperature, wind speed, humidity, and more, for over 200,000 cities globally. The app features an easy-to-use interface, created with Python’s Tkinter library. The app’s key strength lies in its ability to fetch, display, and update weather data in a visually appealing manner using icons and styling elements from **ttkbootstrap**.

## Codes
* The Python code for latest app version can be found [here](https://github.com/nikitaprasad21/Weather-Forecasting-App/blob/main/notebooks/Today's%20Weather%20App%20-%20Upgraded%202.0.ipynb).
* The Python codes for all the previous version can be found [here](https://github.com/nikitaprasad21/Weather-Forecasting-App/tree/main/notebooks).

## Tool Used

  * Used **Python** as the main programming language used to develop the weather app.
  * Used **Tkinter** a built-in Python library for creating the app's graphical user interface (GUI).
  * Used **Requests**, Python library used for fetching real-time weather data via API.
  * Used **PIL (Python Imaging Library)** to add weather icons for a more visual representation of weather conditions.
  * Used **ttkbootstrap** library used to style the app’s user interface, enhancing its visual appeal and functionality.

## Work Process

* Integrated the Open Weather Map API to fetch real-time weather data for any location, with an API key for accessing the Current Weather Data.
* Created a configuration file to securely store the API key for easy retrieval in the **Python** script.
* Developed the app's **GUI using Tkinter**, including various weather parameters such as temperature, wind speed, and humidity.
* Styled the app using the **ttkbootstrap** module and added weather icons with PIL for a polished user experience.
* Implemented features like 10-day weather forecasts and hourly updates to give users comprehensive weather insights.


## Weather Forecasting App 2.0 

![Screenshot 2023-05-20 014620](https://github.com/nikitaprasad21/Weather-Forecasting-App/assets/84131752/b66ac159-fcd5-4b23-bce3-a4b9ade790b8)

## Insights
#### Category 1: Real-time Weather Updates:

  * The app fetches live weather data for any location, ensuring users are always up-to-date with current conditions such as temperature, wind speed, and humidity.
#### Category 2: Multiple Temperature Units:

  * Users can view the temperature in both Celsius and Fahrenheit, making it convenient for different regions with varying unit preferences.

#### Category 3: Visually Appealing Design:

  * The app incorporates weather icons and modern UI elements using the ttk and PIL modules, making it user-friendly and visually engaging.

## Recommendations
#### Category 1: User Notifications:

   * Implement real-time alerts for extreme weather conditions (e.g., storms, heavy rainfall) via push notifications or SMS, which would significantly enhance user safety.
     
#### Category 2: Customizable UI:

   * Allow users to customize the app’s appearance, including themes, icon sets, and temperature unit preferences, making the app more personal and user-centric.
## Assumptions and Caveats
#### Assumptions:

   * The app assumes that the API key provided remains valid and that users have a stable internet connection to fetch real-time weather data.
   * It is assumed that the weather data provided by Open Weather Map is accurate and regularly updated for all global locations.
#### Caveats:

   * The app is dependent on third-party data from the Open Weather Map API, which means any downtime or inaccuracies from the API provider could affect the app’s performance.
   * Certain remote locations or small cities may not have detailed weather data available, leading to partial or missing information for those areas.

## Conclusion

The Weather Forecasting App successfully integrates real-time weather data with a visually appealing and user-friendly interface. It provides accurate and timely weather forecasts for any global location (including over 200,000 cities), offering features such as updates for atmospheric pressure, visibility, humidity, precipitation, wind speed, and multi-unit temperature displays. Future iterations could improve by adding more weather metrics, optimizing performance, and offering enhanced user notifications for severe weather conditions.

**Note**: Steps to create the Configuration file:
  1. Create a text file named "waether_key"on your jupyter notebook.
  2. Write key name enclosed in closed brackets in it as [api].
  3. Create a variable key here I used was "key" and paste the key you copied from the Open Weather Map website.
