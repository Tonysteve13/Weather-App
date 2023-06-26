# Weather-App
# Weather Web App

This is a simple weather web application that allows users to search for weather information of a specific city. It fetches weather data from the OpenWeatherMap API and displays the current temperature, weather description, and minimum and maximum temperatures for the selected city.

## Features

- Input field to enter the city name.
- Search button to fetch weather data for the entered city.
- Displays the city name, country, current weather condition, weather description, and temperature.
- Displays the minimum and maximum temperatures.
- Error handling for invalid city names or empty input.
- Automatically fetches weather data for a default city on page load.

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository or download the source code.
2. Open the `index.html` file in a web browser.

## Usage

1. Enter a city name in the input field.
2. Click the search button or press Enter to fetch weather data for the entered city.
3. The weather information will be displayed below the search box.
4. If the city is not found or the input is empty, an error message will be displayed.

## API Key

To use the OpenWeatherMap API and fetch weather data, you need to provide an API key. Follow these steps to obtain an API key:

1. Go to the [OpenWeatherMap website](https://openweathermap.org/) and sign up for an account.
2. After signing in, go to your account dashboard and navigate to the API Keys section.
3. Generate a new API key or use an existing one.
4. Copy the generated API key.
5. Open the `script.js` file and replace the `key` variable's value with your API key.

```javascript
let key = "YOUR_API_KEY";
```

## Customize

You can customize the application by modifying the CSS styles in the `style.css` file. Feel free to update the colors, fonts, or any other aspect of the design to match your preferences.

## Acknowledgements

This project uses the following resources:

- [OpenWeatherMap API](https://openweathermap.org/api) for fetching weather data.
- [IONICONS](https://ionicons.com/) for the search icon.

## Limitations

- The weather data is fetched from the OpenWeatherMap API, and the accuracy and availability of the data depend on the API's service and data sources.
- The application currently supports only the basic weather information, and additional features like forecasts or more detailed data can be added for enhancement.

## License

This project is licensed under the [MIT License](LICENSE).

## Conclusion

The Weather Web App provides a simple and convenient way for users to check the current weather conditions of a specific city. It demonstrates the use of HTML, CSS, and JavaScript to create a responsive and interactive web application. Feel free to explore, modify, and enhance the project according to your requirements.
