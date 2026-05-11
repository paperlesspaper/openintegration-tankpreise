# OpenPaper Tankstellenkönig Integration

This is Integration showing Gasoline-Prices on [paperlesspaper](https://paperlesspaper.de).

## Overview

This Integration shows gasoline prices fetched from the [tankerkönig-api](https://creativecommons.tankerkoenig.de) and render is for OpenPaper-Displays from the [paperlesspaper project](https://github.com/paperlesspaper).

## How to use

Inside the app select `New Image` > `Custom Integration` and enter the url:
`https://openintegration-caldav.vercel.app/config.json`

## Key files

- [src/render.html](render.html): Static rendering template used for the display.
- [src/config.json](config.json): Simple runtime configuration used by the Open Integrations.

## Deployment

Deploy with Docker by using the Dockerfile.
