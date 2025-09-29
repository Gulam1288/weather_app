# Vibey Weather App 🌤️

A beautiful, modern weather application with a stunning glassmorphism design that provides real-time weather information with dynamic background images that change based on current weather conditions.

![Weather App Interface](https://github.com/user-attachments/assets/251468ed-6d9f-4adb-9317-178436f10d11)

## ✨ Features

### 🎨 Beautiful UI/UX
- **Glassmorphism Design**: Modern glass-effect cards with backdrop blur
- **Dynamic Backgrounds**: Beautiful weather-specific background images that change based on current conditions
- **Responsive Layout**: Fully responsive design that works on desktop, tablet, and mobile devices
- **Smooth Animations**: Elegant fade-in effects and smooth transitions

### 🌍 Weather Information
- **Real-time Weather Data**: Current temperature, weather conditions, and comprehensive metrics
- **Location Support**: 
  - Manual city search with intelligent autocomplete
  - GPS-based location detection
- **Comprehensive Metrics**: 
  - Temperature (°C) with "feels like" temperature
  - Humidity percentage
  - Wind speed (km/h)
  - Precipitation levels (mm)
  - Sunrise and sunset times
  - Daily min/max temperatures

### 📅 Forecasting
- **3-Day Forecast**: Extended weather outlook with daily summaries
- **Hourly Forecast**: Detailed hourly breakdown for the current day
- **Live Clock**: Real-time clock showing local time for the searched location

### 💾 Smart Features
- **Search History**: Automatically saves your last 5 searched cities
- **Quick Access**: One-click access to previously searched locations
- **Error Handling**: Graceful error messages for invalid cities or connection issues
- **Caching**: Intelligent time zone caching for faster repeated searches

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: 
  - [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
  - [Inter Font](https://fonts.google.com/specimen/Inter) - Modern typography
- **APIs**:
  - [WeatherAPI](https://www.weatherapi.com/) - Weather data and forecasting
  - [IP Geolocation API](https://ipgeolocation.io/) - Timezone and location services
- **Storage**: Browser LocalStorage for search history
- **Responsive Design**: Mobile-first responsive layout

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API calls

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Gulam1288/weather_app.git
   cd weather_app
   ```

2. **Open the application**
   
   Simply open `index.html` in your web browser, or serve it using a local server:
   
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Access the application**
   
   Open your browser and navigate to:
   - Direct file: `file:///path/to/weather_app/index.html`
   - Local server: `http://localhost:8000`

### API Configuration

The app comes pre-configured with API keys for demonstration purposes. For production use:

1. **Get a free API key from [WeatherAPI](https://www.weatherapi.com/)**
2. **Get a free API key from [IP Geolocation](https://ipgeolocation.io/)**
3. **Replace the API keys in `index.html`:**
   ```javascript
   const weatherApiKey = "YOUR_WEATHER_API_KEY";
   const apiKey = "YOUR_IPGEOLOCATION_API_KEY";
   ```

## 📱 How to Use

1. **Search by City**: Enter any city name in the search box and press Enter or click the search button
2. **Use Current Location**: Click the location button (📍) to get weather for your current location
3. **View Details**: See comprehensive weather information including:
   - Current temperature and conditions
   - Feels like temperature
   - Humidity, wind speed, precipitation
   - Sunrise and sunset times
   - Hourly forecast for today
   - 3-day extended forecast
4. **Quick Access**: Click on any city in your search history for instant weather updates
5. **Live Updates**: The clock shows real-time local time for the searched location

## 🎯 Features in Detail

### Dynamic Background System
The app automatically selects beautiful background images based on current weather conditions:
- ⛈️ **Thunder/Storms**: Dramatic lightning imagery
- 🌨️ **Snow/Sleet**: Serene winter landscapes  
- 🌧️ **Rain/Drizzle**: Atmospheric rainy scenes
- 🌫️ **Mist/Fog**: Mystical foggy environments
- 💨 **Windy**: Dynamic grass and wind imagery
- ☁️ **Cloudy/Overcast**: Moody cloud formations
- ☀️ **Clear/Sunny**: Bright sunshine (day) or starry night scenes

### Responsive Design
- **Mobile-first**: Optimized for mobile devices
- **Tablet-friendly**: Adapted layout for medium screens
- **Desktop-enhanced**: Full-featured experience on larger screens

## 🌐 Browser Compatibility

- **Chrome** 88+ ✅
- **Firefox** 85+ ✅
- **Safari** 14+ ✅
- **Edge** 88+ ✅

*Note: The app uses modern JavaScript features and CSS properties. Older browsers may not be fully supported.*

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

## 👨‍💻 Author

**Gulam1288**
- GitHub: [@Gulam1288](https://github.com/Gulam1288)

---

Made with ❤️ and modern web technologies