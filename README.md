
# 🌦️🌿 FarmForecast – Weather & Agriculture

**FarmForecast** is a responsive web application that provides detailed weather insights, real-time air quality index (AQI), interactive radar layers, and city-based weather forecasts with smart search, favorites, and geolocation capabilities — all powered by OpenWeatherMap along with agricultural help for diseased plants by Dr.Leaf chatbot.

---

## 🚀 Live Demo

[🔗 Click to view deployed site](https://weather-website-anwesha.netlify.app/) 

---

## 📸 Preview

![ClimateWise Preview](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195045.png)

---

## 📂 Project Structure

```bash
├── 7-day-forecast.css
├── 7-day-forecast.html
├── 7-day-forecast.js
├── Haze.png
├── README.md
├── Screenshots
├── air-quality.css
├── air-quality.html
├── air-quality.js
├── alerts.css
├── alerts.html
├── alerts.js
├── assets
    ├── 404.png
    ├── Haze.png
    ├── Overcast.png
    ├── background.avif
    ├── background.jpg
    ├── background2.jpg
    ├── clear.png
    ├── cloud.png
    ├── location.webp
    ├── loginbackground.webp
    ├── logo.jpg
    ├── mist.png
    ├── nimbus-trans.png
    ├── nimbus.png
    ├── rain.png
    ├── search.png
    ├── smallicon.png
    ├── smoke.webp
    └── snow.png
├── clear.png
├── cloud.png
├── compare-additional.css
├── compare.css
├── compare.html
├── compare.js
├── favorites.css
├── favorites.html
├── favorites.js
├── helpbot.html
├── home.html
├── hourly-forecast.css
├── hourly-forecast.html
├── hourly-forecast.js
├── index.html
├── indexstyle.css
├── map.html
├── map.js
├── mist.png
├── package.json
├── radar.css
├── radar.html
├── radar.js
├── rain.png
├── script.js
├── smoke.webp
├── snow.png
└── style.css
```

---

## ✨ Features

### Login/Register Page
![login](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195435.png)

### Air Quality Index
![air quality](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195319.png)

### 1️⃣ City-Based Favorites Dashboard

- Add favorite cities and fetch their current weather instantly.
- Store data persistently in `localStorage`.
- See real-time info like temperature, humidity, wind, and icon preview.
- Remove cities dynamically from your favorites list.

![comparison](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195353.png)
![](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195404.png)

### 2️⃣ Hourly Forecast Viewer

- View detailed hourly forecasts in 3-hour intervals (up to 48 hours).
- Temperature, weather condition, wind speed, and humidity.
- Dynamic scrollable cards with AM/PM format.
- Switch between 24h and 48h with a toggle button.

![Hourly](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195205.png)

### 3️⃣ Interactive Weather Radar Map

- Real-time radar visualization using **Leaflet.js** and 

![Weather Radar](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195239.png)

**OpenWeatherMap tile layers**.
- Supports:
  - 🌧️ Precipitation
  - ☁️ Cloud Cover
  - 🌬️ Wind Flow
  - 🌡️ Temperature
  - 📉 Pressure
- Play/Pause radar animation with step forward/backward
- Geolocated marker popup with current weather description

![Map](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195119.png)

### 4️⃣ Smart Search (Landing Page)

- Search for any city and get instant weather data.
- Uses **OpenWeatherMap Current Weather API**
- Displays:
  - Temperature (with icons)
  - Feels Like
  - Humidity
  - Wind Speed
  - Sunrise/Sunset Time
  - Visibility
- ❤️ Add/remove city from Favorites
- 📍 Locate me button using browser's Geolocation

### 5️⃣ Persistent Storage with localStorage

- Stores:
  - Favorite cities
  - Last searched city
  - Last weather data (for offline-first behavior)
- Restores state automatically on reload

### 6️⃣ Geolocation Support

- Uses browser's `navigator.geolocation` API to fetch and display weather for your current location.
- Converts latitude & longitude to nearest city and displays weather data

### 7️⃣ Responsive & User-Friendly UI

- Custom weather icons based on weather status
- Toast alerts (via `react-hot-toast` or native `alert`)
- Dynamic DOM updates without page reload
- Fully responsive across mobile, tablet, and desktop

### 7-Day Forecast

![7dayforecast](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195139.png)

### Weather Alerts
![alerts](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195256.png)

### 🌿 Dr. Leaf – Agriculture Disease Diagnosis Chatbot

**Dr. Leaf** is an AI-powered agriculture assistant built using **Botpress**. It helps farmers and researchers diagnose plant diseases and manage crop health effectively.

🧠 **Trained on:**
- Hosta Virus Dataset
- PlantVillage Dataset
- Agriculture Disease Management Data

💬 **Features:**
- Diagnoses plant issues based on user input
- Suggests treatments for diseases like Yellow Mosaic Virus, Rust, Leaf Spot, and Root Rot
- Provides integrated pest and disease management advice

🚀 Powered by Botpress Cloud | Built with farmers in mind

🔗 Try it live or integrate into your farming advisory systems.

![agribot](https://github.com/anwesha24-code/WeatherWebsite/blob/973adafc857de2c5b9cd815e7ed6823cfd622563/Screenshots/Screenshot%202025-08-02%20181451.png)
![chats](https://github.com/anwesha24-code/WeatherWebsite/blob/1f7a7ba40baba0f086217612986d3e4045316bc2/Screenshots/Screenshot%202025-08-02%20181646.png)
---

## 🛠️ Built With

- **HTML5, CSS3, JavaScript**
- **Leaflet.js** for maps
- **OpenWeatherMap API**
- **Font Awesome** for icons
- **localStorage API**

---

## ⚙️ Installation

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/weather-website.git
cd weather-website
```

### 2. Add Your API Key

Replace the `apiKey` placeholder in all JS files with your own from [OpenWeatherMap](https://openweathermap.org/api).

```js
const apiKey = "YOUR_API_KEY_HERE";
```

### 3. Run Locally

Open `index.html` in a browser or use a local server like:

```bash
npx live-server
```

---

## 🔐 Environment Notes

- **API Key security**: This app uses client-side JS. Don't expose sensitive usage-heavy API keys without quota limits.
- For production, consider moving API logic to a backend server.

---

## 📌 To-Do / Improvements

- [ ] Add AQI (Air Quality Index) charts
- [ ] Add dark mode toggle
- [ ] Add forecast graph view using Chart.js or Recharts
- [ ] PWA support (installable version)
- [ ] Deploy to Netlify/Vercel

---

## 🧠 Author

**Anwesha Pal**

> *Weather lover. Clean coder. UI/UX explorer.*

---
