# WeatherWidget

This project is a simple yet powerful weather application that fetches and displays current weather data for
any city. It's designed to be an easy-to-use tool for anyone interested in quickly accessing weather information.

## Project Overview

**WeatherWidget** leverages the Open-Meteo API to provide real-time weather updates. With just a few clicks, users can get the current
temperature, wind speed, weather conditions, and local time for any city in the world. The app also includes a visualization feature that
displays the temperature using color-coded bars for a quick visual reference.

## Journey

Ensuring accurate local time was crucial, achieved by converting UTC time provided by the API to the city's local time using the `pytz`
library. Furthermore, handling and parsing JSON data from API responses efficiently was crucial for seamlessly extracting and displaying
relevant weather information. Moreover, building a user-friendly and interactive interface with `ipywidgets` was entirely new to me, yet
it was essential for providing a smooth user experience and definitely a cool new learning milestone.

## Contribute

Contributions are welcome, although the whole thing is unfolding as a relatively small project. Everyone is able to use the code, play
around or extend it. Have fun!

## License

**WeatherWidget** is released under the MIT License. You are free to use, modify, and distribute the code for both commercial and non-commercial purposes.
