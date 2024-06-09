# Weather Application

This is a simple weather application that allows users to get the current weather information for any city. 
The application uses the OpenWeatherMap API to fetch and display the weather data.

## Features

- Search for current weather by city name.
- Displays temperature, humidity, wind speed, and weather conditions.
- Shows appropriate icons based on the weather conditions.
- Handles invalid city names with an error message.

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Getting Started

### Prerequisites

To run this project, you need a web browser and an internet connection.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/arslansalyana/js-weather-app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd weather-application
    ```

### Running the Application

1. Open `index.html` in your preferred web browser.
2. Enter a city name in the input field and click the search button to get the weather information for that city.

## Usage

- **Search for a City:** Enter the name of the city you want to get the weather for and click on the search button.
- **View Weather Information:** The weather information including temperature, humidity, wind speed, and an appropriate weather icon will be displayed.
- **Error Handling:** If an invalid city name is entered, an error message will be shown.

## Project Structure

- `index.html` - The main HTML file that contains the structure of the application.
- `styles.css` - The CSS file that contains the styles for the application.
- `images/` - A directory containing the weather icons and search icon used in the application.
- `script.js` - The JavaScript file that contains the logic for fetching and displaying the weather data.

## API Key

This project uses the OpenWeatherMap API. You need to replace the `apiKey` variable in `script.js` with your own API key from OpenWeatherMap.

```javascript
const apiKey = 'your-api-key-here';
