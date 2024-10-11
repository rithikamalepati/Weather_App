This project is a WEATHER FORECASTING WEB APPLICATION built using Flask for the backend and HTML, CSS, and JavaScript for the frontend. The app allows users to input a city name and retrieve real-time weather data, including temperature and weather conditions such as "Clear," "Clouds," or "Rain," which are displayed with relevant emojis.

*Frontend (HTML/CSS/JavaScript):

The interface consists of a text input for the city name and a button to fetch the weather.
When the "Get Weather" button is clicked, the app sends a request to the backend to retrieve the weather for the entered city.
The weather conditions are displayed in a user-friendly way, with an emoji corresponding to the weather condition.

*Backend (Flask):

The backend uses Flask to handle requests and serves the front-end files.
It communicates with the OpenWeatherMap API to fetch weather data based on the city name entered by the user.
The API response is processed and returned to the frontend to display the results.

*Weather API Integration:

The app integrates the OpenWeatherMap API to retrieve real-time weather data for any city.
The weather data includes temperature (in Fahrenheit) and a description of the weather condition.

*Error Handling:

If the user enters an invalid city name or if there's an issue fetching the data, the app displays an error message.
