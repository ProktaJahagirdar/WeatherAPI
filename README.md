# WeatherAPI

A simple web application that provides current weather information and a 5-day forecast for any given city.

### Features
- **Search for Weather**: Enter a city name to get the current weather.
- **Five-Day Forecast**: Displays a 5-day weather forecast for the searched city.

### Technologies Used
- **Backend**: Java, Spring Boot
- **Frontend**: JSP Pages, JavaScript, HTML, CSS
- **UI**: Bootstrap 4
- **Libraries**: JSTL, Joda-Time Library
- **API**: Open Weather Map API (via RapidAPI)

### How It Works
1. The application fetches weather data from the Open Weather Map API.
2. The data is parsed and displayed on JSP pages, showing the current weather and a 5-day forecast.
3. The app allows users to search for weather by city, including cities with the same name in different countries (e.g., London in the USA).

### Setup
- Clone the repository.
- Configure the API connection to Open Weather Map via RapidAPI.
- Run the Spring Boot application.
