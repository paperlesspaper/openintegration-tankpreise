# OpenPaper Tankstellenkönig Integration

This Integration is showing Gasoline-Prices on [paperlesspaper](https://paperlesspaper.de).

## Overview

This Integration shows gasoline prices fetched from the [tankerkönig-api](https://creativecommons.tankerkoenig.de) and render is for OpenPaper-Displays from the [paperlesspaper project](https://github.com/paperlesspaper).

## How to use

Inside the app select `New Image` > `Custom Integration` and enter your custom url to your config.json (e.g. tankstelle.paperlesspaper.de/config.json)

1. You need to register for API Key at creativecommons.tankerkoenig.de
2. You need to find a proper Station ID, you can search one at [your-url]/stationsnummer (e.g. tankstelle.paperlesspaper.de/stationsnummer )
3. Add API Key and StationID to the settings of your custom Integration in the paperlesspaper app.
4. to show correct timestamps, choose a timezone
5. save and wait for updates of prices on your openPaper-Displays.

## Key files

- [src/render.html](render.html): Static rendering template used for the display.
- [src/config.json](config.json): Simple runtime configuration used by the Open Integrations.

## Deployment

Deploy with Docker by using the Dockerfile.
