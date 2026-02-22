# Weather App

## Overview

This project is a responsive weather application that allows users to search for current weather conditions by city name. It uses the OpenWeatherMap API to first retrieve geographic coordinates (latitude and longitude) and then fetch real-time weather data based on those coordinates.

The application demonstrates asynchronous JavaScript, API integration, and dynamic DOM manipulation.

---

## Features

- Search weather by city name  
- Input validation with user-friendly error messages  
- Geocoding API integration to retrieve latitude and longitude  
- Real-time weather data fetching  
- Temperature conversion from Kelvin to Celsius  
- Dynamic weather icon display  
- Responsive and clean UI design  
- Conditional rendering of weather results  

---

## Technologies Used

### Frontend
- HTML5  
- CSS3  
- Vanilla JavaScript  

### API
- OpenWeatherMap  
- Geocoding API  
- Current Weather Data API  

---

## How It Works

- The user enters a city name and clicks “Search.”  
- The app validates the input to ensure it is not empty.  
- A request is sent to the OpenWeatherMap Geocoding API to retrieve longitude and latitude.  
- If a valid city is found, a second request is made to the Weather API using the retrieved coordinates.  
- The weather data (temperature, description, icon) is dynamically displayed on the page.  
- The temperature is converted from Kelvin to Celsius before rendering.  

---

## Project Structure

```
/weather-app
 ├── index.html
 ├── styles.css
 └── script.js
```

---

## Key Learning Outcomes

- Working with async/await in JavaScript  
- Handling API responses and HTTP errors  
- Using fetch for external API requests  
- Manipulating the DOM dynamically  
- Implementing input validation  
- Structuring small frontend projects  
