#weather app
   ->A simple weather app that fetches real-time weather data for a given city using the [openweatherMap API](https://openweatherMap.org/api).
   ->The app displays the current temperature,with month,date,year and time.
##Features
->real-time weather data for any city.
->Displays current temperature,and weather description.
simple and clean UI using jQuery and css.
##technologies used
->**html/css**: For the user interface.
->**javascript (jQuery)**: To fetch and manipulate data.
->**open weatherMapAPI**: To format the date and time.
- *Moment.js*: To format the date and time.

## Setup

1. *Clone the repository:*

    bash
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    

2. *Sign up for OpenWeatherMap API:*

   - Go to [OpenWeatherMap](https://openweathermap.org/api) and sign up to get your API key.
   - 3. *Configure the API Key:*

   - Open script.js and replace the placeholder API key with your own:

     javascript
     const apiKey = 'YOUR_API_KEY_HERE';
     

4. *Run the Application:*

   - You can simply open index.html in your browser to run the app.

## Usage

- On page load, the app will show the weather of a default city (e.g., Pune).
- You can modify the default city in the JavaScript code or add an input field to allow users to search for different cities.
- ## Code Overview

### HTML

- index.html: Contains the structure of the weather information, including elements for city name, temperature, description, wind speed, and a placeholder for the weather icon.
- ### JavaScript

- script.js: Contains the main logic of the application.
  - Uses jQuery to make an API request, update the DOM with weather details, and set the appropriate icon based on the weather description.


  - License

This project is licensed under the MIT License.

Acknowledgments

OpenWeatherMap for providing free access to weather data.

FontAwesome for any additional icons used.

Inspired by simple weather web apps available online.





