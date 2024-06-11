# Weather App

This is a simple weather application that fetches weather data using the OpenWeatherMap API and displays the current weather and a 6-day forecast. It includes functionality to search for weather information by city name and toggle between Celsius and Fahrenheit temperature units.

## Features

- **Current Weather Information**: Displays the current temperature, city name, weather description, humidity, wind speed, date, and weather icon.
- **6-Day Weather Forecast**: Provides a 6-day weather forecast with maximum and minimum temperatures and weather icons.
- **City Search**: Allows users to search for weather information by city name.
- **Temperature Unit Conversion**: Users can switch between Celsius and Fahrenheit temperature units.

## Installation

To run the application locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/weather-app.git
   cd weather-app

2. Open index.html in your favorite web browser.

# Usage
## Searching for a City

1. Enter the name of the city in the search input field.
2. Click the "Search" button or press Enter.

## Switching Temperature Units
Click on the "°F" link to display temperatures in Fahrenheit.
Click on the "°C" link to switch back to Celsius.
# Code Overview
## HTML Structure
The main elements in `index.html`:

`#search-form`: The form for searching weather by city name.
`#city-input`: The input field for entering the city name.
`#temperature`: The element displaying the current temperature.
`#city`: The element displaying the city name.
`#description`: The element displaying the weather description.
`#humidity`: The element displaying the humidity level.
`#wind`: The element displaying the wind speed.
`#date`: The element displaying the current date and time.
`#icon`: The element displaying the weather icon.
`#forecast`: The element displaying the 6-day weather forecast.
`#fahrenheit-link`: The link for switching to Fahrenheit.
`#celsius-link`: The link for switching to Celsius.
## JavaScript Functions
**formatDate**: Formats a timestamp into a readable day and time string.
**formatDay**: Converts a timestamp to a short day string (e.g., "Sun").
**displayForecast**: Displays the 6-day weather forecast.
**getForecast**: Fetches the weather forecast data from OpenWeatherMap API.
**displayTemperature**: Displays the current weather information.
**search**: Initiates a search for weather information based on city name.
**handleSubmit**: Handles the form submission for searching a city.
**showFahrenheitTemperature**: Converts and displays the temperature in Fahrenheit.
**showCelsiusTemperature**: Converts and displays the temperature in Celsius.

## Event Listeners
**Form Submission**: Listens for the form submission to trigger the city search.
**Temperature Unit Conversion**: Listens for clicks on the Fahrenheit and Celsius links to toggle temperature units.

## API Key
The OpenWeatherMap API key is included in the code. If you want to use your own API key, replace the apiKey variable value in the getForecast and search functions.

```sh
let apiKey = "your-own-api-key";
