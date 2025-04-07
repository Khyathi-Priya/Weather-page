Weather Page Using API Key

## Project Overview

This project is a simple weather web application that allows users to search for weather information based on a city name. It fetches real-time weather data using a third-party weather API and displays essential details such as temperature, weather condition, humidity, and more. The project is built using HTML, CSS, and JavaScript, with an API integration to get the weather data. Users can quickly get the current weather and related information for any city worldwide.

## Features

- **Search Weather by City:** Users can enter a city name to get the current weather.
- **Real-time Data:** Displays weather data in real-time including temperature, humidity, and weather condition.
- **Responsive Design:** Mobile-friendly interface that adapts to different screen sizes.
- **Simple User Interface:** Clean and user-friendly layout for easy interaction.

## Technologies Used

- **HTML:** For structuring the content of the webpage.
- **CSS:** For styling the webpage and ensuring a responsive design.
- **JavaScript:** For handling user input, API requests, and displaying weather data dynamically.
- **OpenWeatherMap API (or other weather API):** For fetching weather data based on city name.
  
## How It Works

1. **User Input:** The user enters a city name into a search box.
2. **API Request:** The JavaScript code sends a request to the OpenWeatherMap API with the provided city name.
3. **Data Fetching:** The API returns weather data in JSON format, which includes temperature, weather description, humidity, and more.
4. **Display Data:** The weather information is displayed on the webpage for the user to see.

### Example API Request:
```javascript
const url = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}&units=metric`;
