# 🌦️ Django Weather Forecast App

A clean and simple Django web application that displays real-time weather data using the OpenWeatherMap API. Users can search by city name and view temperature, humidity, wind speed, and climate conditions.

<h2>## 🚀 Features </h2>

- 🔍 Search weather by city name
- 🌐 Real-time weather using OpenWeatherMap API
- 📍 Auto-fetch city latitude & longitude (via Geocoding API)
- 🌡️ Display temperature, humidity, wind speed
- 🖼️ SVG-based modern UI icons
- 📦 Built with Django and Python


<h2> 📁 Project Structure </h2>

  weather_project/<br>
│                <br>
├── templates/    <br>
│   └── index.html    <br>       
│                   <br>
├── static/        <br>
│   └── style.css      <br>      
│                  <br>
├── weather/  <br>
│   └── views.py      <br>
│            <br>
├── manage.py      <br>
└── requirements.txt        <br>


🧱 Tech Stack

Backend: Python, Django <br>
Frontend: HTML, CSS (custom), Jinja2 templating <br>
API: OpenWeatherMap    <br>


🌐 How It Works

User submits a city name.   <br>
App sends a request to OpenWeatherMap Geocoding API to get lat and lon.  <br>
Then fetches weather data using the latitude and longitude. <br>
Parses and displays temperature, humidity, wind speed, and climate info.<br>


