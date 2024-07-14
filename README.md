# Python_Weather_App

## Overview

The Weather App is a graphical user interface (GUI) application that provides current weather information for a specified city. The application uses the Tkinter library for the interface, Geopy for geolocation, and TimezoneFinder for timezone information. It fetches weather data from the OpenWeatherMap API.

## Features

- Search for weather information by city name.
- Display current temperature, weather conditions, wind speed, humidity, description, and pressure.
- Show local time for the searched city.

## How It Works

### Main Screen

- Search Box: Enter the name of the city you want to get weather information for.
- Search Button: Click to fetch and display the weather information.

### Weather Information:

- Temperature: Displays the current temperature in Celsius.
- Condition: Shows the main weather condition (e.g., Clear, Rain).
- Wind: Displays the wind speed.
- Humidity: Shows the humidity percentage.
- Description: Provides a description of the weather condition.
- Pressure: Displays the atmospheric pressure.


## Code Explanation:

### Imported Libraries:
- tkinter and tk: Used for the graphical user interface.
- geopy.geocoders.Photon: For geolocation.
- timezonefinder: For finding the timezone of a location.
- datetime: For handling date and time.
- requests: For making API calls.
- pytz: For timezone handling.

### Function:

- getWeather(): Fetches and displays the weather information for the entered city.

### GUI Elements

- Search Box: An entry widget for entering the city name.
- Search Button: A button to trigger the weather fetch.
- Logo: Displays the application logo.
- Bottom Box: A frame to hold the weather information labels.
- Time: Displays the local time of the searched city.
- Weather Information Labels: Labels to display wind speed, humidity, description, and pressure.

  
### Error Handling

- Displays an error message if the entered city is invalid.

### Notes

- Displays an error message if the entered city is invalid.

### Example

- Open the application.
- Enter "London" in the search box.
- Click the search button.
- The application will display the current weather information for London.
