# airvisual-json-charts
Uses charts.js to display JSON data from a single IQAir AirVisual Pro device. It looks like this:

![Example Chart](https://morris.cloud/airvisual-json-charts/airvisual-json-charts_demo.jpg)

To use this, drop it into a web server (or just download it and open it as a local file in your web browser) and update the URL using your AirVisual Pro's API link, see [docs here](https://support.iqair.com/en/articles/3029330-how-to-access-the-airvisual-pro-s-api) for how to get the link for yours.

This repo version has a link to a static JSON file for demo purposes. You can see this page rendered (with that static data) [here](https://morris.cloud/airvisual-json-charts/), which basically looks like the graph above but you can hover for datapoint info.

As of this initial commit, the PM2.5 is displaying as micrograms per cubic liter. Eventually I hope to add in the US and Chinese AQI conversions. 

Note that anyone who has this page after you put in your Pro's API link will then thereafter have that URL and the data from it. So using this is pretty much the same as making your Pro's data public. 

I'm not affiliated with IQAir. 
