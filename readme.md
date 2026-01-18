# Weather App

A simple and elegant weather application that displays real-time weather information for any city in the world.

## Features

- 🔍 **City Search**: Search for weather information by entering any city name
- 🌡️ **Temperature Display**: Shows current temperature in Celsius
- 💧 **Humidity**: Displays current humidity percentage
- 💨 **Wind Speed**: Shows wind speed in km/h
- 🎨 **Weather Icons**: Dynamic weather icons that change based on weather conditions
- 📱 **Responsive Design**: Works on desktop and mobile devices
- ✨ **Error Handling**: Displays error messages for invalid city names

## Supported Weather Conditions

- ☁️ Clouds
- ☀️ Clear
- 🌧️ Rain
- 🌦️ Drizzle
- 🌫️ Mist

## Technologies Used

- **HTML5**: Structure and layout
- **CSS3**: Styling with gradient backgrounds and flexbox
- **JavaScript (ES6)**: Async/await for API calls and DOM manipulation
- **OpenWeatherMap API**: Real-time weather data

## How to Use

1. Open `index.html` in your web browser
2. Enter a city name in the search box
3. Click the search button or press Enter
4. View the current weather information for that city

## Project Structure

```
weather-app/
├── index.html      # Main HTML file with embedded JavaScript
├── styles.css      # Styling for the weather app
├── images/         # Weather and UI icons
│   ├── search.png
│   ├── humidity.png
│   ├── wind.png
│   ├── clouds.png
│   ├── clear.png
│   ├── rain.png
│   ├── drizzle.png
│   └── mist.png
└── README.md       # Project documentation
```

## API Key

This app uses the **OpenWeatherMap API**. The API key is embedded in the code. For production use, consider:
- Storing the API key in environment variables
- Using a backend server to hide the API key
- Implementing rate limiting

To get your own API key, visit [OpenWeatherMap](https://openweathermap.org/api)

## Installation

No installation required! Simply open the `index.html` file in any modern web browser.

## Browser Compatibility

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)

## Styling Details

- **Color Scheme**: Gradient from cyan (#00feba) to purple (#5b5483)
- **Background**: Dark (#222)
- **Font**: Poppins (Google Fonts)
- **Max Width**: 470px for optimal viewing

## Future Enhancements

- Add forecast for multiple days
- Implement geolocation to auto-detect user's location
- Add temperature unit toggle (Celsius/Fahrenheit)
- Save favorite cities
- Add weather alerts
- Implement dark/light theme toggle

## License

This project is open source and available for personal and educational use.

## Author

Created as part of the 30 Days JavaScript Project challenge.
