# Dashboard Chrome Extention

This is a simple Chrome extension that enhances the user's browsing experience with nature-themed backgrounds, real-time cryptocurrency data, current time, and local weather information.

## Features

1. **Nature-Themed Backgrounds**: The extension fetches random landscape-oriented nature images from the Unsplash API and sets them as the background of the document body. If the API request fails, a default image is used.

2. **Cryptocurrency Data**: The extension fetches real-time data about Bitcoin from the CoinGecko API and displays the name, current price, 24-hour high, and 24-hour low in Euros.

3. **Current Time**: The extension displays the current time, updated every second.

4. **Local Weather**: The extension fetches the user's geolocation and uses it to retrieve local weather data from the OpenWeatherMap API. It displays the temperature and the name of the location.

## Error Handling

The extension has robust error handling. If any API request fails, an error message is logged to the console. For the Unsplash API, a default image and author are used in case of failure.

## Additional Files

This project also includes CSS and HTML files for styling and structure, respectively.
