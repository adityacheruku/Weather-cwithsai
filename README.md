# Weather App

This project is a simple weather application that allows users to get the current weather information for any location. The app uses the OpenWeatherMap API to fetch and display weather data.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Dependencies](#dependencies)
- [Customization](#customization)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    ```

2. Open the project directory in your code editor.

3. Serve the application using a local server. 

   Open your browser and navigate to `http://localhost:3000`.

## Usage

1. Open the application in your browser.
2. Enter the name of the location in the search box and press the search button or hit the "Enter" key.
3. The app will display the current weather information for the entered location, including temperature, weather description, humidity, and wind speed.
4. If the location is not found, an error message will be displayed.

## File Structure

- **images/**: Contains images used in the app.
- **index.html**: The main HTML file for the application.
- **index.js**: JavaScript file containing the logic for fetching and displaying weather data.
- **style.css**: CSS file for styling the application.
- **README.md**: Documentation for the project.

## Dependencies

The project relies on the following external libraries and resources:

- [Google Fonts](https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&family=Roboto:wght@300;400;500;700;900&display=swap)
- [Font Awesome](http://kit.fontawesome.com/7c8801c017.js)
- [OpenWeatherMap API](https://openweathermap.org/api)

## Customization

### HTML

The main structure of the weather application is defined in the `index.html` file. You can customize the appearance and layout by modifying the HTML elements and their attributes.

### CSS

The styles for the weather application are defined in `style.css`. You can modify the styles to match your design preferences.

### JavaScript

The core functionality of the weather application is implemented in `index.js`. You can enhance the app's capabilities or modify its behavior by updating the JavaScript code.

#### API Key

Replace the `APIkey` variable in `index.js` with your own OpenWeatherMap API key:

```javascript
const APIkey = 'your_api_key_here';

