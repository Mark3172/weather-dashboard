# ⛅ WeatherAI — Advanced Weather Dashboard & AI Assistant

An ultra-modern, glassmorphism weather dashboard featuring **zero-scroll compact responsive layout**, **real-time weather intelligence**, **interactive "Ask AI" assistant**, **Air Quality Index (AQI)**, **GPS Geolocation**, and **dynamic canvas atmosphere effects**.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-v18%2B-green.svg)](https://nodejs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![OpenWeatherMap](https://img.shields.io/badge/API-OpenWeatherMap-orange.svg)](https://openweathermap.org/)

---

## ✨ Features

- **📱 Zero-Scroll 2-Column Layout**: High-density balanced grid designed so all vital atmospheric data, forecasts, and AI insights fit comfortably on your screen without vertical scrolling.
- **🤖 Interactive "Ask AI" Assistant**: 
  - Conversational weather assistant analyzing 40-data-point / 5-day forecasts.
  - Interactive prompt bar with quick-action chips (*"Car Wash?"*, *"Need Umbrella?"*, *"Best Run Time?"*, *"Dry Clothes?"*, *"Weekend Outlook?"*).
  - Real-time typewriter animation effect.
- **📍 GPS Geolocation ("My Location")**: One-click coordinate detection to automatically pull hyper-local weather.
- **🍃 Live Air Quality Index (AQI)**: Color-coded air quality gauge (*Good, Fair, Moderate, Poor, Very Poor*) with real PM2.5 and PM10 particulate levels.
- **⭐ Favorites & Bookmarks System**: Save favorite cities to persistent local storage with instant 1-click chip switching.
- **📤 One-Click Share Weather Report**: Formats and copies a clean, emoji-rich weather summary to your clipboard for WhatsApp, Telegram, or Slack.
- **🌅 Glowing Sun Schedule Arc**: Quadratic bezier sky scene displaying the real-time position of the sun, animated sunrise/sunset times, and daylight progress tracking.
- **📈 Smooth Temperature Trend Chart**: Dynamic SVG dual-bezier curve showing daily high/low temperatures with gradient area fills.
- **🕐 24-Hour Hourly Forecast**: Smooth-scrolling horizontal strip highlighting current and upcoming conditions.
- **🌌 Dynamic Atmosphere Engine**:
  - Weather-reactive animated background gradient orbs (sunny gold, rainy slate, snowy silver, night indigo).
  - Canvas-based dynamic particle system (rainfall streaks, drifting snowflakes, or floating atmospheric motes).
  - Twinkling 80-star celestial field.
- **⚡ Dual Mode (Live API & Demo Preview)**:
  - Connect your free OpenWeatherMap API key for live global data.
  - Interactive offline demo mode with multi-city realistic simulation (*Tokyo, London, New York, Sydney, Dubai, Paris*).

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/Mark3172/weather-dashboard.git
cd weather-dashboard
```

### 2. Run the local dev server
```bash
npm run dev
```

Open your browser at **[http://localhost:5173](http://localhost:5173)** (or your designated port).

*Alternatively, simply open `index.html` directly in any modern web browser — no dependencies required!*

---

## 🔑 OpenWeatherMap API Setup (Optional)

1. Sign up for a free API key at [OpenWeatherMap](https://openweathermap.org/).
2. Click the **"API Key"** button in the dashboard header.
3. Paste your key and click **"Save & Use Live Data"**.
4. Your key is saved locally in your browser's `localStorage` and never sent to external servers.

---

## 📂 Project Structure

```
weather-dashboard/
├── index.html       # Complete frontend application (HTML5, CSS3, ES6+ JavaScript)
├── server.js        # Zero-dependency local development server with auto-port fallback
├── package.json     # Project metadata and dev scripts
└── README.md        # Documentation and feature guide
```

---

## 🛠️ Built With

- **HTML5 & Vanilla CSS3**: CSS Grid, Flexbox, Glassmorphism, CSS Custom Properties.
- **Modern JavaScript (ES6+)**: Canvas Particle API, Geolocation API, Clipboard API, Async/Await.
- **OpenWeatherMap REST API**: Current Weather, 5-Day/3-Hour Forecast, and Air Pollution Endpoints.
- **Node.js HTTP**: Zero-dependency local static server.

---

## 📄 License

This project is licensed under the MIT License — feel free to use, modify, and distribute.
