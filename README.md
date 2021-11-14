ClockDisplay
============

Raspberry pi wall display including weather and indoor temperatures

### About

This is a Node Red project that is intended to be a wall display. The current implementation is running on a Raspberry Pi connected to an old video monitor mounted on the wall.  

Originally this was run on a Raspberry Pi Zero W. It would run on that hardware but after several days of running it had a tendency to lock up. I think that was due to the limited memory on the Pi Zero. Switching to a Raspberry Pi Model 3B solved the problem. In theory this could run on any computer that can run Node Red and a web browser.  

The files are in a format that can be used by the Node Red project feature. You should be able to clone this project using the Node Red project menu.  

The analog clock code is based on the example in [Old School Clock with CSS3 and jQuery](https://css-tricks.com/css3-clock/) by Toby Pitman.

[Raspberry Pi Kiosk using Chromium](https://pimylifeup.com/raspberry-pi-kiosk/) was used as a starting point for setting up the Raspberry Pi to start up with the browser as the display.  

You can find the National Weather Service API documentation [at this link](https://www.weather.gov/documentation/services-web-api#/default/get_stations__stationId__observations_latest) .  

The Pokemon API interface documentation can be found [at this link](https://pokeapi.co/docs/v2). This applies to the Pokemon of the Day feature branch.

Check out the [Wiki for this project](https://github.com/NSE-labs/ClockDisplay/wiki) for more information.