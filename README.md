# Weather4Me Web App

This is the source code for the web application running at https://wx4.me.

## What this web app does

When visiting this web page from a mobile device, it will prompt the user to provide their location using a standard browser geolocation API. This location data is then cross-referenced against active US [National Weather Service](https://weather.gov/) severe weather alerts. The majority of these alerts since 2007 have been outlined based on geographic polygons rather than political subdivisions or county-equivalents. The user is then informed whether their device's location is inside one of these warning polygons. 

### Additional weather data referenced
* US Storm Prediction Center severe convective weather watches
* US Storm Prediction Center severe convective outlooks for Day 1 (today) and Day 2 (tomorrow)
* Current weather conditions at the nearest National Weather Service observation site
* National Weather Service forecast for the first upcoming forecast period

## Contributing
You are welcome to fork this repository and open pull requests to improve the application. This web app is hosted on the Azure Static Web App service, so all operations must be client-side.

## Respect the Polygon
"Respect the Polygon" is a phrase popularized by legendary Alabama television meteorologist James Spann. It is meant to remind his audience that forecasters at the National Weather Service are experts in their field, and if a given location is inside one of these storm-based warning polygons, there is a very good reason for it. Anyone inside the warning polygon should take action to protect themselves from natural hazards. This app is my effort to help people quickly determine whether they should take these actions.