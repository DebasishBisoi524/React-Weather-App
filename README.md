React Weather App
A responsive weather application built with React that provides real-time weather information for cities worldwide. Users can search for any city to view current weather conditions and a 5-day forecast.


Features
Current Weather Data: Displays temperature, humidity, wind speed, and weather conditions (e.g., clear, cloudy, rain).

5-Day Forecast: Shows a daily weather forecast for the next 5 days.

City Search: Search for any city to get its weather details.

Responsive Design: Works seamlessly on both desktop and mobile devices.

Weather Icons: Visual icons representing different weather conditions.

Technologies Used
React: Frontend framework for building the user interface.

CSS Modules: For styling components.

OpenWeatherMap API: Provides real-time and forecast weather data.

Installation
Clone the repository:

bash
Copy
git clone https://github.com/DebasishBisoi524/React-Weather-App.git
cd React-Weather-App
Install dependencies:

bash
Copy
npm install
Get an API Key:

Sign up for a free account at OpenWeatherMap.

Generate an API key under the "API Keys" section.

Set Up Environment Variables:

Create a .env file in the root directory.

Add your API key:

Copy
VITE_APP_ID=your_api_key_here
Run the app:

bash
Copy
npm start
The app will open at http://localhost:3000.

Usage
Enter a city name in the search bar (e.g., "London").

View current weather details and the 5-day forecast.

The app will display temperature (°C), humidity (%), wind speed (m/s), and weather conditions.

API Reference
This app uses the OpenWeatherMap API endpoints:

Current Weather: https://api.openweathermap.org/data/2.5/weather

5-Day Forecast: https://api.openweathermap.org/data/2.5/forecast

Contributing
Contributions are welcome! Follow these steps:

Fork the repository.

Create a new branch for your feature: git checkout -b feature-name.

Commit your changes: git commit -m "Add feature-name".

Push to the branch: git push origin feature-name.

Open a pull request.
