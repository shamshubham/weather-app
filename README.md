# Weather App

A simple web-based weather application that allows users to search for weather information of different cities. It provides real-time weather updates including temperature, humidity, and wind speed.

## Features

- **City Search**: Enter a city name to retrieve weather information.
- **Weather Display**: Shows current temperature, humidity, and wind speed for the selected city.
- **Weather Icons**: Displays appropriate weather icons based on the current weather conditions.
- **Error Handling**: Displays an error message if the city name is invalid or not found.

## Getting Started

To use the Weather App, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd weather-app
   ```

2. **Open the HTML File**:
   Open the `index.html` file in your web browser to start using the Weather App.

## How It Works

1. **Search for a City**:

   - Enter a city name in the input field and click the search button.
   - The application fetches weather data from the OpenWeatherMap API.

2. **View Weather Information**:

   - Displays the city name, current temperature, humidity, and wind speed.
   - Shows an appropriate weather icon based on the weather conditions (e.g., clouds, clear, rain).

3. **Error Handling**:
   - If an invalid city name is entered or the city is not found, an error message is displayed.

## API

The Weather App uses the [OpenWeatherMap API](https://openweathermap.org/api) to retrieve weather data. An API key is required to access the weather data.

- **API Key**: `540edaaffb3ef183697e2f4236a80d79`
- **Endpoint**: `https://api.openweathermap.org/data/2.5/weather?units=metric&q=`

## Customization

You can customize the Weather App by:

- **Changing the API Key**: Replace the existing API key with your own if needed.
- **Updating Weather Icons**: Replace weather icons in the `images` folder with your preferred icons.
- **Styling**: Modify the `style.css` file to change the look and feel of the application.

## Dependencies

- **None**: This project uses plain HTML, CSS, and JavaScript without any external libraries or frameworks.

## Contribution

To contribute to this project:

1. **Fork the Repository**: Create a personal copy of the repository on GitHub.
2. **Create a Feature Branch**: Develop new features or fixes in a separate branch.
3. **Commit Changes**: Add and commit your modifications.
4. **Push to the Branch**: Push your changes to your forked repository.
5. **Create a Pull Request**: Submit a pull request to propose your changes.

## License

This project is open-source and available under the [MIT License](LICENSE). You can freely use, modify, and distribute the code under the terms of the license.

## Contact

For questions or feedback, please reach out via the contact information provided in the repository.

---

Feel free to adjust this README file to better fit your project's specific details and requirements.
