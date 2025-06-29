# 🌦️ Django Weather Forecast App

A clean and simple Django web application that displays real-time weather data using the OpenWeatherMap API. Users can search by city name and view temperature, humidity, wind speed, and climate conditions.

## 🚀 Features

- 🔍 Search weather by city name
- 🌐 Real-time weather using OpenWeatherMap API
- 📍 Auto-fetch city latitude & longitude (via Geocoding API)
- 🌡️ Display temperature, humidity, wind speed
- 🖼️ SVG-based modern UI icons
- 📦 Built with Django and Python


📁 Project Structure

  weather_project/
│
├── templates/
│   └── index.html               # Main UI page
│
├── static/
│   └── style.css                # Custom styling
│
├── weather/
│   └── views.py                 # Handles API call and data
│
├── manage.py
└── requirements.txt


🧱 Tech Stack

Backend: Python, Django
Frontend: HTML, CSS (custom), Jinja2 templating
API: OpenWeatherMap


🌐 How It Works

User submits a city name.
App sends a request to OpenWeatherMap Geocoding API to get lat and lon.
Then fetches weather data using the latitude and longitude.
Parses and displays temperature, humidity, wind speed, and climate info.


