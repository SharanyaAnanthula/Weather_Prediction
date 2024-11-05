WeatherPrediction

WeatherPrediction is a dynamic weather forecasting web application built with HTML, CSS, and JavaScript. 
It retrieves real-time weather data for cities worldwide using an API and displays information such as temperature, humidity, wind speed, and sunrise and sunset times. 
Based on the weather conditions of the selected city, the application updates the background with a relevant weather image for a more immersive experience.

Features:-

Real-Time Weather Data:

Get up-to-date weather information for any city.

Detailed Forecast:

View city-specific details, including temperature, humidity, wind speed, and sunrise and sunset times.

Dynamic Background: 

The background changes based on the current weather in the selected city (e.g., sunny, cloudy, rainy).

Simple, Intuitive Interface: Clean design and user-friendly layout.

Technologies Used:-

HTML: 

For structuring the web application.

CSS:

For styling and responsive design.

JavaScript: 

For fetching data from the weather API and dynamically updating the UI.

Project Structure:-

.
├── index.html               # Main HTML file
├── style.css                # Styling for the application
├── script.js                # JavaScript file for handling API calls and data manipulation
├── images                   # Folder containing background images
└── README.md                # Project documentation

Getting Started:-

1.Clone the repository:

git clone https://github.com/your-username/weatherprediction.git

cd weatherprediction

2.Set up API access:

Register with a weather data provider (e.g., OpenWeatherMap) to obtain an API key.

In script.js, replace YOUR_API_KEY with your actual API key.

3.Open the project:

Launch index.html in your web browser to view the application.

Usage:-

1.Enter a City:

In the search box, type the name of the city you want to look up.

2.View Weather Details: 

The app will fetch and display:

Temperature

Humidity

Wind Speed

Sunrise and Sunset times

3.Dynamic Background:

The background updates based on the weather conditions in the city.

Sample API Response (OpenWeatherMap):-

{
  "name": "London",
  "main": {
    "temp": 15.0,
    "humidity": 80
  },
  "weather": [
    {
      "main": "Rain",
      "description": "light rain"
    }
  ],
  "wind": {
    "speed": 4.5
  },
  "sys": {
    "sunrise": 1603093200,
    "sunset": 1603136100
  }
}
