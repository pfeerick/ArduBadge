[![Maintainability](https://api.codeclimate.com/v1/badges/9dfc74cb3e65fb4dcd84/maintainability)](https://codeclimate.com/github/gilmaimon/Arduino-Library-Manager-Badge/maintainability) [![dependencies Status](https://david-dm.org/gilmaimon/Arduino-Library-Manager-Badge/status.svg)](https://david-dm.org/gilmaimon/Arduino-Library-Manager-Badge)

# Arduino Library-Manager Badge

With the `Arduino Library-Manager` "Badge" you can notify your users and GitHub visitors that your library is available for download via the built-in Arduino IDE [`Library Manager`](https://www.arduino.cc/en/guide/libraries).

The badge will show whether the library is available in the Library Manager and if so, what is the latest release available. Clicking on the badge will open up explanation for new users on how to install libraries with the Library Manager and Arduino IDE.

## Getting Started
In order to get a badge for your library, all you need to do is to add this markdown in your readme page:
```markdown
[![arduino-library-badge](http://arduino-library-badge.gilmaimon.xyz/badge/LIBRARY_NAME.svg)](https://www.arduino.cc/en/guide/libraries)
```
Just replace `LIBRARY_NAME` with your own library name.

### Examples
Exisitng Libraries:  
  
[![arduino-library-badge](http://arduino-library-badge.gilmaimon.xyz/badge/ArduinoCloudStorage.svg)](https://www.arduino.cc/en/guide/libraries) [![arduino-library-badge](http://arduino-library-badge.gilmaimon.xyz/badge/ArduinoComponents.svg)](https://www.arduino.cc/en/guide/libraries) [![arduino-library-badge](http://arduino-library-badge.gilmaimon.xyz/badge/FastLED.svg)](https://www.arduino.cc/en/guide/libraries) [![arduino-library-badge](http://arduino-library-badge.gilmaimon.xyz/badge/HttpClient.svg)](https://www.arduino.cc/en/guide/libraries) [![arduino-library-badge](http://arduino-library-badge.gilmaimon.xyz/badge/MQTT.svg)](https://www.arduino.cc/en/guide/libraries) [![arduino-library-badge](http://arduino-library-badge.gilmaimon.xyz/badge/ArduinoJson.svg)](https://www.arduino.cc/en/guide/libraries)

Non-Existing Libraries:  
  
[![arduino-library-badge](http://arduino-library-badge.gilmaimon.xyz/badge/NoWay.svg)](https://www.arduino.cc/en/guide/libraries) [![arduino-library-badge](http://arduino-library-badge.gilmaimon.xyz/badge/Not%20A%20Real%20Library.svg)](https://www.arduino.cc/en/guide/libraries)

## Contributing
Contributions are welcomed!
This section should help you get started.
### Dependencies
In order to have your own instance of the server, you need to first have:
#### Software Dependencies
- MongoDB instance
- Node.js & NPM

#### Node.js Dependencies
- express
- mongoose
- request
- gunzip-file
- download-file
- rimraf
### Installing and Deployment
Clone the repository, and run:
1. ```npm install``` - to install all Node.js dependencies
2. ```npm start``` - to start up the server

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details

## Coming Up
- Clicking the badge will redirect to a custom page for explaining how to get specifically your library via the arduino IDE
- Dedicated Domain Name and Server (moving to port 80)
- Website with github integration
