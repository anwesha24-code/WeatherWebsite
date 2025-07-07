
# 🌦️ ClimateWise – Weather & AQI Dashboard

**ClimateWise** is a responsive web application that provides detailed weather insights, real-time air quality index (AQI), interactive radar layers, and city-based weather forecasts with smart search, favorites, and geolocation capabilities — all powered by OpenWeatherMap.

---

## 🚀 Live Demo

[🔗 Click to view deployed site](#) *(Add your Netlify/Vercel link here)*

---

## 📸 Preview

![ClimateWise Preview](preview.png)

---

## 📂 Project Structure

```bash
taskmate-app/
├── index.html
├── home.html
├── hourly.html
├── radar.html
├── styles/
│   └── main.css
├── scripts/
│   ├── main.js
│   ├── home.js
│   ├── hourly.js
│   └── radar.js
├── assets/
│   ├── weather-icons/
│   └── images/
└── README.md
```

---

## ✨ Features

### 1️⃣ City-Based Favorites Dashboard

- Add favorite cities and fetch their current weather instantly.
- Store data persistently in `localStorage`.
- See real-time info like temperature, humidity, wind, and icon preview.
- Remove cities dynamically from your favorites list.

### 2️⃣ Hourly Forecast Viewer

- View detailed hourly forecasts in 3-hour intervals (up to 48 hours).
- Temperature, weather condition, wind speed, and humidity.
- Dynamic scrollable cards with AM/PM format.
- Switch between 24h and 48h with a toggle button.

### 3️⃣ Interactive Weather Radar Map

- Real-time radar visualization using **Leaflet.js** and **OpenWeatherMap tile layers**.
- Supports:
  - 🌧️ Precipitation
  - ☁️ Cloud Cover
  - 🌬️ Wind Flow
  - 🌡️ Temperature
  - 📉 Pressure
- Play/Pause radar animation with step forward/backward
- Geolocated marker popup with current weather description

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
git clone https://github.com/your-username/taskmate-app.git
cd taskmate-app
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

## 📜 License

This project is licensed under the [MIT License](LICENSE).
