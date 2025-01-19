# weather-app
A simple and responsive weather app that provides real-time weather updates. Users can search for cities, view the weather conditions, toggle between Celsius and Fahrenheit, and enjoy a dynamic background based on the weather. The app supports geolocation for getting weather in the user's current location and saves the last searched city.

![Weather App](https://i.imgur.com/G7DnHVt.png)

## Features:
- **City search** with autocomplete suggestions
- **Toggle unit:** switch between Celsius (°C) and Fahrenheit (°F)
- **Weather data:** displays temperature, humidity, wind speed, and weather conditions
- **Location-based weather:** Get weather using your current location
- **Responsive design:** Works seamlessly on desktops and mobile devices
- **Dynamic background:** Background changes based on the weather conditions (e.g., sunny, rainy, cloudy).
- **Loader while fetching data** to indicate loading state.
- **Save last searched city** to display it as the default on the next session.

## Technologies Used:
- HTML
- CSS
- JavaScript
- OpenWeatherMap API
- Nominatim API (for city autocomplete)
- Geolocation API

## Installation:

### 1. Clone the repository:
  git clone https://github.com/your-username/weather-app.git

2. Navigate to the project folder:
  cd weather-app

3. Open the index.html file in your preferred web browser to start using the app.

  API Key: 
  You will need an API key from OpenWeatherMap.

  To get your API key:
  1. Visit OpenWeatherMap.
  2. Sign up for a free account and get your API key.
  3. Store your API key securely and create a config.js file to keep it safe.

  Create config.js to store your API Key:

    1. Create a new file named config.js in the project directory.

    2. Inside config.js, add your API key as shown below:

      // config.js

      const config = {
      API_KEY: 'YOUR_API_KEY_HERE'
      };

      export default config;

    3. Make sure to add config.js to your .gitignore file   to keep it secure and prevent accidental pushes to version control:
    

Note: Never expose your API key in public repositories. For production environments, consider using secure methods to handle API keys such as environment variables.

