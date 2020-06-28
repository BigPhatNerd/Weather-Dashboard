# 06 Server-Side APIs: Weather Dashboard

Developers are often tasked with retrieving data from another application's API and using it in the context of their own. Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. Your challenge is to build a weather dashboard that will run in the browser and feature dynamically updated HTML and CSS.

Use the [OpenWeather API](https://openweathermap.org/api) to retrieve weather data for cities. The documentation includes a section called "How to start" that will provide basic setup and usage instructions. Use `localStorage` to store any persistent data.

## User Story

AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly

## Pseudocode

* search for a city to presented with current and future conditions for that city and that city is added to the search history
* view current weather conditions for that city to presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
* view the UV index to presented with a color that indicates whether the conditions are favorable, moderate, or severe
* view future weather conditions for that city to presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity
* click on a city in the search history to again presented with current and future conditions for that city
* open the weather dashboard to presented with the last searched city forecast
