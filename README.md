# 🌦️ React Weather App

A responsive weather application built with **React** that provides real-time weather data and a 5-day forecast for cities around the world. Users can search any city to view current temperature, humidity, wind speed, and conditions like rain, clear, or clouds.

---

## ✨ Features

- **🔍 City Search** – Type any city name to get real-time weather data.
- **📊 Current Weather** – Shows temperature (°C), humidity, wind speed, and weather condition.
- **📅 5-Day Forecast** – Daily weather predictions for the next 5 days.
- **🖼️ Weather Icons** – Visual icons for different weather types (sunny, cloudy, rainy, etc.).
- **📱 Responsive Design** – Works great on mobile phones, tablets, and desktops.

---

## 🛠️ Tech Stack

- **React** – Frontend framework
- **CSS Modules** – For component-level styling
- **OpenWeatherMap API** – Weather data provider

---

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/DebasishBisoi524/React-Weather-App.git
cd React-Weather-App
Install dependencies:

bash
Copy
Edit
npm install
Get your API Key:

Sign up at OpenWeatherMap.

Navigate to API Keys and generate your key.

Set up environment variables:

Create a .env file in the root directory:

env
Copy
Edit
VITE_APP_ID=your_api_key_here
Start the development server:

bash
Copy
Edit
npm run dev
App will run at http://localhost:5173

🚀 Usage
Type a city name (e.g., "London") into the search bar.

Hit Enter or click the search icon.

View:

Current temperature

Humidity

Wind speed

Weather condition & icon

Scroll to view the 5-day forecast (if implemented).

🔗 API Reference
Powered by OpenWeatherMap:

Current Weather:
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}

5-Day Forecast:
https://api.openweathermap.org/data/2.5/forecast?q={city}&appid={API_KEY}

🤝 Contributing
Contributions are welcome!

Fork the repo

Create a feature branch:

bash
Copy
Edit
git checkout -b feature-name
Commit your changes:

bash
Copy
Edit
git commit -m "Add feature-name"
Push your branch:

bash
Copy
Edit
git push origin feature-name
Create a Pull Request
