### React/Redux Weather App

A simple weather app using react/redux. Search for a city to get a convenient chart with weather for the next five days.

Checkout this repo, install dependencies, then start the gulp process with the following:

```
> git clone
> cd weather
> npm install
> npm start

```

This project will not work without an API key from http://openweathermap.org/. Obtain a key and then create a file in the src/ directory called config.js. Add an object called apiKeys in config.js containing your API key and export it, edit /actions/index.js accordingly and the app should work fine. It takes about ten minutes for http://openweathermap.org/ to generate a working key.