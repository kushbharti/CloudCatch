# 🌦️ Django Weather Forecast App

A clean and simple Django web application that displays real-time weather data using the OpenWeatherMap API. Users can search by city name and view temperature, humidity, wind speed, and climate conditions.

![Screenshot 2025-07-06 130556](https://github.com/user-attachments/assets/f5860138-4ac3-49f6-bd42-6992790d406b)<br><br>
![Screenshot 2025-07-06 130628](https://github.com/user-attachments/assets/3ff08ca4-97d3-4789-a95a-92b8539221be)<br><br>
![Uploading Screenshot 2025-07-06 130652.png…]()<br> <h2 align='center'>Interface </h1> <br>


<h1>🚀 Features </h1>

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
│   └── index.html      
│                   <br>
├── static/        <br>
│   └── style.css        
│                  <br>
├── weather/  <br>
│   └── views.py      
│            <br>
├── manage.py      <br>
└── requirements.txt        <br>


<h2> 🧱 Tech Stack </h2>

Backend: Python, Django <br>
Frontend: HTML, CSS (custom), Jinja2 templating <br>
API: OpenWeatherMap    <br>


<h2> 🌐 How It Works </h2>

User submits a city name.   <br>
App sends a request to OpenWeatherMap Geocoding API to get lat and lon.  <br>
Then fetches weather data using the latitude and longitude. <br>
Parses and displays temperature, humidity, wind speed, and climate info.<br>


