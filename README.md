
# 🌤️ Weather Monitoring App

This Weather Monitoring App uses the OpenWeather API to provide real-time weather data for any location. It includes essential features such as temperature alerts, unit conversion, and detailed weather metrics like humidity, minimum, maximum, and average temperature.

## 🚀 Features

- **Temperature Alert**: Alerts when the temperature exceeds 35°C.
- **Temperature Conversion**: Easily convert temperatures between Celsius and Fahrenheit.
- **Detailed Weather Data**:
  - Humidity
  - Average Temperature
  - Minimum and Maximum Temperature
  
## 🛠️ Tech Stack

- **Frontend**: React.js
- **API**: [OpenWeather API](https://openweathermap.org/api)
- **Backend**:node.js

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone  https://github.com/D-D-Roshan/Weather-application.git
   ```
2. Navigate to the project folder:
   ```bash
   cd weather-applicationg-app
   ```
3. Install dependencies (if any):
   ```bash
   npm install
   ```

4. Get your OpenWeather API key from [here](https://openweathermap.org/api).

5. Create a `.env` file in the root directory and add your API key:
   ```bash
   REACT_APP_OPENWEATHER_API_KEY=your_api_key
   ```

## 🌦️ Usage

1. Open in your browser or run the app using:
   ```bash
   npm start
   ```
2. Enter the desired location (city, country) in the search bar to get weather data.
3. The app will display:
   - Current Temperature (with the option to convert between Celsius and Fahrenheit)
   - Humidity
   - Min/Max/Avg Temperature
4. If the temperature exceeds 35°C, an alert will pop up.

## 📊 Key Metrics Displayed

- **Current Temperature**: Convert between °C and °F.
- **Humidity**: The current humidity level in the selected location.
- **Average, Min, Max Temperature**: Daily average, minimum, and maximum temperatures.

## 🔔 Temperature Alerts

The app will notify the user with an alert if the current temperature exceeds 35°C.

## 📸 Sample Screenshot

![Weather Monitoring App Screenshot](https://github.com/D-D-Roshan/Weather-application/blob/main/public/Screenshot%20(100).png)

## 🌐 Live Demo

Try out the live demo [here](https://hazzweather.netlify.app/).

## 🤝 Contributing

Feel free to contribute to this project by submitting a pull request. Please ensure your changes are well-documented.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

