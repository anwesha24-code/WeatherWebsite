# 🌦️ Nimbus – Weather & AQI Dashboard

**Nimbus** is a responsive web application that delivers detailed weather insights, real-time air quality index (AQI), interactive radar maps, hourly and daily forecasts, and city-based weather dashboards with smart search, favorites, and geolocation — all powered by **OpenWeatherMap**.

---

## 🚀 Live Demo

[🔗 Click here to view the deployed site](#) *(Replace this with your Netlify/Vercel deployment link)*

---

## 📸 Preview

![ClimateWise Preview](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195045.png)

---

## 📂 Project Structure

```
weatherWebsite/
├── script.js
├── index.html               # Landing/search page
├── 7-day-forecast.js
├── 7-day-forecast.html
├── 7-day-forecast.css
├── air-quality.js
├── air-quality.html
├── air-quality.css
├── alerts.js
├── alerts.html
├── alerts.css
├── compare-additional.css
├── compare.css
├── compare.html
├── compare.js
├── favorites.css
├── favorites.html
├── favorites.js
├── home.html                # Dashboard with favorites
├── hourly-forecast.html              # Hourly forecast
├── hourly-forecast.js
├── hourly-forecast.css
├── index.html
├── indexstyle.css
├── map.html
├── map.js
├── radar.css
├── radar.js
├── radar.html               # Radar view with layers
└── README.md
```

---

## ✨ Features

### 🔐 Login/Register Page

![Login](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195435.png)

---

### 🏩 City-Based Favorites Dashboard

* Add favorite cities and see their weather at a glance.
* Persistent storage using `localStorage`.
* Get temperature, humidity, wind, icons, and more.
* Remove cities anytime with one click.

![Favorites](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195353.png)
![](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195404.png)

---

### ⏰ Hourly Forecast Viewer

* View forecasts in 3-hour intervals for up to 48 hours.
* Data includes temperature, weather description, wind, and humidity.
* Toggle between 24h and 48h views.
* Clean scrollable card layout with AM/PM format.

![Hourly](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195205.png)

---

### 🗺️ Interactive Weather Radar Map

* Real-time weather radar using **Leaflet.js** and **OpenWeatherMap tile layers**.
* Toggle between layers:

  * 🌧️ Precipitation
  * ☁️ Clouds
  * 🌬️ Wind
  * 🌡️ Temperature
  * 📉 Pressure
* Play/pause animation, and step through time.
* City marker with pop-up weather description.

![Radar](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195239.png)
![Map](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195119.png)

---

### 🔍 Smart Search (Landing Page)

* Search any city and get instant weather data.
* Displays:

  * 🌡️ Temperature
  * 🌡️ Feels Like
  * 💧 Humidity
  * 💨 Wind Speed
  * 🌅 Sunrise / 🌇 Sunset
  * 👁️ Visibility
* ❤️ Add/remove from favorites
* 📍 Use browser geolocation to get your current city weather

---

### ☁️ Air Quality Index (AQI)

![AQI](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195319.png)

---

### 🗓️ 7-Day Forecast

![7-Day Forecast](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195139.png)

---

### ⚠️ Weather Alerts

![Alerts](https://github.com/anwesha24-code/WeatherWebsite/blob/a6f011384a725cea107f8e7f1394be084ddd0bda/Screenshots/Screenshot%202025-07-07%20195256.png)

---

## 💾 Persistent Storage

* Saves:

  * Favorite cities
  * Last searched location
  * Last fetched weather data (for offline use)
* Automatically restores data on reload

---

## 📍 Geolocation Support

* Uses `navigator.geolocation` API
* Converts lat/lon to city name using OpenWeatherMap
* Displays real-time weather for current location

---

## 💻 Responsive & User-Friendly UI

* Custom icons & illustrations
* Smooth DOM updates
* Mobile-first responsive layout
* Uses FontAwesome, native alerts, and visually engaging styles

---

## 🛠️ Tech Stack

* **HTML5 + CSS3 + JavaScript**
* **Leaflet.js** for maps
* **OpenWeatherMap API**
* **Font Awesome**
* **localStorage API**

---

## ⚙️ Installation Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/anwesha24-code/WeatherWebsite.git
cd WeatherWebsite
```

### 2️⃣ Set Up Your API Key

Replace all instances of the placeholder API key in JS files:

```js
const apiKey = "YOUR_API_KEY_HERE";
```

You can get your free key from [OpenWeatherMap](https://openweathermap.org/api).

### 3️⃣ Run the App Locally

Open `index.html` in your browser directly or use a local server like:

```bash
npx live-server
```

---

## 🛡️ Environment Notes

* ⚠️ API keys are exposed on the client side.
* Set rate limits on your API key.
* For production: use a backend proxy or serverless function for secure requests.

---

## 🔧 Future Improvements

* [ ] Integrate AQI charts
* [ ] Dark mode toggle
* [ ] Forecast graphs using Chart.js
* [ ] Add PWA support (Installable)
* [ ] Deploy to Netlify/Vercel

---

## 👩‍💻 Author

**Anwesha Pal**

> Weather Enthusiast · Passionate Developer · UI/UX Explorer

🌐 [GitHub](https://github.com/anwesha24-code)
📧 [anweshapal@example.com](mailto:anweshapal@example.com) *(replace with your real email if needed)*

---

## 📄 License

Licensed under the [MIT License](LICENSE).
