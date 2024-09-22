# Weather Web App

A simple and user-friendly weather web application that provides real-time weather information for any city around the world. This app allows users to search for a city and receive detailed weather data, including temperature, humidity, wind speed, and weather conditions, along with a 5-day forecast.

## Features

- **Current Weather Data**: Displays real-time weather information such as temperature, humidity, wind speed, and weather conditions.
- **5-Day Forecast**: Provides a forecast for the next 5 days with high/low temperatures and expected conditions.
- **Search by City**: Users can search for any city around the world to get local weather data.
- **Responsive Design**: Works seamlessly across different screen sizes including mobile and desktop.
- **Location-based Weather**: Automatically fetches weather data for the user's current location if allowed.
- **Clean and Intuitive UI**: Provides a simple and interactive user experience.

## Table of Contents

1. [Demo](#demo)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Future Improvements](#future-improvements)
6. [License](#license)

## Demo


Try the live demo here: [Link to Deployed App](#)

## Technologies Used

- **Frontend**:
  - HTML5
  - CSS3
  - JavaScript (ES6+)
  - React.js

- **API**:
  - OpenWeatherMap API for real-time weather data and 5-day forecasts

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/weather-web-app.git
    cd weather-web-app
    ```

2. Install the required dependencies:

    ```bash
    npm install
    ```

3. Get your API key from [OpenWeatherMap](https://openweathermap.org/).

4. Create a `.env` file in the root of the project and add your API key:

    ```
    REACT_APP_WEATHER_API_KEY=your_api_key
    ```

5. Start the development server:

    ```bash
    npm start
    ```

6. Open the app in your browser at `http://localhost:3000`.

## Usage

1. Enter a city name in the search box to get the weather information for that location.
2. View the current temperature, weather condition, humidity, and wind speed.
3. Check the 5-day forecast to plan ahead.
4. If allowed, the app will fetch your current location’s weather data automatically.
5. Enjoy the simple, easy-to-navigate interface.

## Future Improvements

- **Unit Conversion**: Add functionality to switch between Celsius and Fahrenheit.
- **Geolocation Enhancements**: Improve accuracy for location-based weather searches.
- **Enhanced UI/UX**: Add animations and additional visual elements to improve user engagement.
- **Hourly Forecast**: Include detailed hourly weather data.
- **Weather Maps**: Integrate weather maps to visualize conditions like rain, wind, and temperature variations across regions.
