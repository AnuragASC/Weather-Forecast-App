# Weather-Forecast-App

Welcome to the Weather Forecast App! This application provides real-time weather information for any location. The app is built using HTML, CSS, and JavaScript.

# Features

Real-time weather information
Displays temperature in Celsius or Fahrenheit
Shows weather conditions, UV index, wind status, humidity, visibility, and air quality
Daily and weekly forecasts
Dynamic background and icons based on weather conditions

# Installation

To run the Weather Forecast App locally, follow these steps:

1.Clone the repository:
git clone https://github.com/yourusername/weather-forecast-app.git

2.Navigate to the project directory:
cd weather-forecast-app

3.Open index.html in your preferred web browser.

# Usage

Enter the name of the city in the search bar and press enter or click the search button.
The app will display the current weather information and forecast for the entered city.
Use the toggle buttons to switch between Celsius and Fahrenheit.
Switch between daily and weekly forecasts using the respective buttons.

# API Reference

This application uses the Visual Crossing Weather API to fetch weather data.

Base URL: https://weather.visualcrossing.com/VisualCrossingWebServices/rest/services/timeline/
Example endpoint: https://weather.visualcrossing.com/VisualCrossingWebServices/rest/services/timeline/{city}?unitGroup=metric&key={API_KEY}&contentType=json
Replace {city} with the desired city and {API_KEY} with your Visual Crossing API key.

# File Structure

weather-forecast-app/
│
├── index.html      # Main HTML file
├── style.css       # CSS styles
├── script.js       # JavaScript file
└── README.md       # Project README file

# Code Explanation

index.html
The HTML file sets up the structure of the app, including the search form, weather display sections, and buttons for unit and forecast toggles.

style.css
The CSS file contains styles for the layout, including the sidebar, main content area, and various elements like buttons, weather icons, and text formatting.

script.js
The JavaScript file handles fetching data from the Visual Crossing Weather API, updating the DOM with weather information, and managing user interactions like unit toggles and forecast switches.
