# Weather App

A simple and responsive weather application that provides real-time weather information for any city around the world. Built with HTML, CSS, and JavaScript using the OpenWeatherMap API.

## Features

- **Real-time Weather Data**: Get current weather information for any city
- **Temperature Display**: Shows temperature in Celsius
- **Weather Conditions**: Displays weather icons based on conditions (Clouds, Clear, Rain, Drizzle, Mist, Snow)
- **Humidity & Wind Speed**: Shows additional weather details including humidity percentage and wind speed in KM/h
- **Error Handling**: Displays user-friendly message when city is not found
- **Responsive Design**: Clean and modern card-based UI that works on different screen sizes
- **Search Functionality**: Easy-to-use search bar to look up any city

## Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and responsive design
- **JavaScript (ES6+)** - Fetching API data and DOM manipulation
- **OpenWeatherMap API** - Real-time weather data

## Project Structure

```
Weather__App/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── README.md           # Project documentation
└── images/             # Weather icons and assets
    ├── clear.png
    ├── clouds.png
    ├── drizzle.png
    ├── humidity.png
    ├── mist.png
    ├── rain.png
    ├── search.png
    ├── snow.png
    └── wind.png
```

## Setup and Installation

1. **Clone or download** this repository to your local machine.

2. **Get an API Key**:
   - Sign up at [OpenWeatherMap](https://openweathermap.org/)
   - Navigate to the API keys section
   - Generate a new API key

3. **Add your API Key**:
   - Open `index.html`
   - Replace the existing API key in the JavaScript section with your own:
   ```javascript
   const apiKey = "your_api_key_here";
   ```

4. **Run the Application**:
   - Open `index.html` in any modern web browser
   - No additional server or build process required

## Usage

1. Open the application in your web browser
2. Enter the name of any city in the search box
3. Click the search button (or press Enter)
4. View the current weather information including:
   - Temperature
   - City name
   - Weather condition with icon
   - Humidity percentage
   - Wind speed

## API Reference

This application uses the [OpenWeatherMap Current Weather Data API](https://openweathermap.org/current).

- **Base URL**: `https://api.openweathermap.org/data/2.5/weather`
- **Parameters**:
  - `q`: City name
  - `units`: metric (for Celsius)
  - `appid`: Your API key

## Customization

- **Default City**: You can change the default city displayed on load by modifying the `checkWeather()` call at the bottom of the script in `index.html`.
- **Styling**: Customize colors, fonts, and layout in `style.css`.
- **Units**: To display temperature in Fahrenheit, change `units=metric` to `units=imperial` in the API URL.

## Browser Compatibility

- Chrome
- Firefox
- Safari
- Edge
- Opera

## License

This project is open source and available for personal and educational use.

## Acknowledgments

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
- Icons and images included in the project

