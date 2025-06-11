# WeatherApp
 A basic weather application project typically involves creating a user interface using HTML, CSS, and  JavaScript to display weather information for a specific location
Features
Live Weather Data: Get up-to-date weather information for your current location or search for any city worldwide.
5-Day Forecast: View a 5-day weather forecast for your chosen city.
Explore Section: Discover weather information for various random cities in the explore section.
Add More Cities: You can add and save more cities for quick access to their weather.
Technologies Used
Frontend: HTML, CSS, JavaScript
API: OpenWeatherMap
Icons: Font Awesome
API Endpoints
The application utilizes the following OpenWeatherMap API endpoints:
Geocoding API: To get location names (city or area) using longitude and latitude.
https://openweathermap.org/api/geocoding-api
Current Weather Data: To retrieve current weather conditions.
https://openweathermap.org/current
5-Day Forecast: To obtain a 5-day weather forecast.
https://openweathermap.org/forecast5
Getting Started
To get a local copy of the Weather App up and running, follow these simple steps.
Prerequisites
A modern web browser.
An API key from OpenWeatherMap.
Installation
Clone the repository:
Bash
git clone https://github.com/kaushalsahu07/weather.git


Navigate to the project directory:
Bash
cd weather


Replace "Your API Key" with your actual OpenWeatherMap API key in all JavaScript files:
JavaScript
let apiKey = "Your API Key";


Open index.html in your web browser to view the project.
Usage
To use the Weather App, simply enter the name of the city in the search bar and press Enter. The app will display the current weather conditions, including temperature, humidity, wind speed, and more.
