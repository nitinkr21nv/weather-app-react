# 🌦️ Weather App

A responsive weather application built with **React.js** that provides real-time weather information using the **OpenWeather API**. Users can search for any city worldwide and view current weather details such as temperature, humidity, weather condition, minimum & maximum temperature, and feels-like temperature.

---

## 🚀 Live Demo

🔗 **Live Demo:** https://weather-app-react-eta-vert.vercel.app/

---

# ✨ Features

- 🔍 Search weather by city name
- 🌡️ View real-time temperature
- 💧 Display humidity
- 📈 Display minimum & maximum temperature
- 🤗 Display "Feels Like" temperature
- ☁️ Show current weather description
- ❌ Error handling for invalid city names
- ⚡ Fast API integration
- 📱 Responsive user interface

---

# 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript (ES6+)
- HTML5
- CSS3

### API
- OpenWeather API

### Tools
- Vite
- Git
- GitHub
- Vercel

---

# 📂 Folder Structure

```text
weather-app-react/
│── public/
│── src/
│   ├── assets/
│   ├── SearchBox.jsx
│   ├── InfoBox.jsx
│   ├── WeatherApp.jsx
│   ├── App.jsx
│   ├── main.jsx
│── screenshots/
│── package.json
│── vite.config.js
│── README.md
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/weather-app-react.git
```

## Navigate to Project

```bash
cd weather-app-react
```

## Install Dependencies

```bash
npm install
```

## Start Development Server

```bash
npm run dev
```

---

# 🔑 Environment Variables

Create a `.env` file in the root directory.

```env
VITE_WEATHER_API_KEY=YOUR_OPENWEATHER_API_KEY
```

Access the API key inside your project using:

```javascript
const API_KEY = import.meta.env.VITE_WEATHER_API_KEY;

---

# 🌐 API Used

This project uses the **OpenWeather API** to fetch live weather information.

Website:

https://openweathermap.org/api

---

# 💻 How It Works

1. User enters the city name.
2. React sends a request to the OpenWeather API.
3. API returns weather information in JSON format.
4. React updates the UI dynamically.
5. Invalid city names display an error message.

---

# 👨‍💻 Author

**Nitin Kumar**

---

