# Weather Station with NodeMCU ESP8266, OLED Display, and DHT11 Sensor
Prepared by: 
Name: NUR EZURIN FARISHA BINTI JUSSHAIRI 
Matric No: 284253
## Overview

This project combines the power of NodeMCU ESP8266, an OLED display, and a DHT11 sensor to create a weather station that provides real-time temperature, humidity, and weather forecast information. The weather data is fetched from the OpenWeatherMap API.

![Weather Station Demo](demo.gif)

## Features

- Displays current temperature, humidity, and weather condition icon on an OLED display.
- Shows a forecast for the upcoming days.
- Automatically updates weather data at regular intervals.
- Uses NodeMCU ESP8266 microcontroller for IoT connectivity.
- Simple and affordable components: NodeMCU ESP8266, OLED display, and DHT11 sensor.
- Customizable and expandable for additional features.

## Components

- NodeMCU ESP8266 microcontroller.
- SSD1306 OLED display.
- DHT11 temperature and humidity sensor.

## Dependencies

- Arduino IDE
- Libraries:
  - ESPWiFi
  - ESPHTTPClient
  - JsonListener
  - SSD1306Wire
  - OLEDDisplayUi
  - OpenWeatherMapCurrent
  - OpenWeatherMapForecast
  - WeatherStationFonts
  - WeatherStationImages
  - DHT

## Installation

1. Install the Arduino IDE and required libraries.
2. Clone or download this repository to your local machine.
3. Open the `weather_station.ino` file in the Arduino IDE.
4. Connect the NodeMCU ESP8266, OLED display, and DHT11 sensor to your development board.
5. Upload the sketch to your NodeMCU ESP8266 board.

## Usage

1. Power on your NodeMCU ESP8266 board.
2. The weather station will automatically fetch and display weather data on the OLED display.
3. Use the OLED display navigation buttons to switch between different views (time/date, temperature, humidity, forecast).
4. Enjoy real-time weather updates at a glance!

## Contributing

Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and submit a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this template according to your project's specific details and requirements!
