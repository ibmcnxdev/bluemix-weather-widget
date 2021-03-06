# bluemix-weather-widget

## Setup
- Add bluemixWeatherWidget.json application to your Conenctions organisation
- In the JSON, replace the placeholder `[your-community-id]` with the UUID of the community to which you wish to add the widget
- Ensure the include-files property pulls the correct path referencing the bluemixWeatherWidget.js file

## Description
This Customizer application adds a Weather widget to the community overview page of a chosen community. Or by removing the `match` property entirely from the JSON, the widget will be added to every community's overview page. The widget houses an iframe, which contains the following src: https://xpages-fusion-alchemy.mybluemix.net/xpagesFusionAlchemy.nsf/weather.xsp. This is an XPages application running in Bluemix. It leverages the "[Weather Comany Data](https://www.ng.bluemix.net/docs/services/Weather/index.html)" service from Bluemix, to provide current weather conditions, a 24 hour forecast and a 10 day forecast. 

## Screenshots

![Screenshot 1](https://ibm.box.com/shared/static/lujh63aus7b9c2nattgqu6keptninnun.png)
![Screenshot 2](https://ibm.box.com/shared/static/m194260achid5o5leufc41gx0uganodc.png)
![Screenshot 3](https://ibm.box.com/shared/static/6rngrh580dbw2t4ofalh4ba4d8cezlwh.png)
