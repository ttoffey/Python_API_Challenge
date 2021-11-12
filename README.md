# Python_API_Challenge - What is the weather like as you approach the Equator?

![Equator](Images/equatorsign.png)

## **Requirements**

## Part I - WeatherPy

In this example, you'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you'll be utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

The first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot, add a sentence or two explaining what the code is analyzing.

The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, take the time to explain what the linear regression is modeling. For example, describe any relationships you notice and any other analysis you may have.

## Part II - VacationPy

Use jupyter-gmaps and the Google Places API to plan a future vacation. 

## **Summary**

>A point is referenced by is longitude and latitude (http://desktop.arcgis.com/en/arcmap/10.3/guide-books/map-projections/about-geographic-coordinate-systems.htm).

>Latitude lines run from east-west and longitude lines run from north-south - Northern and Southern Hemispheres. Latitude lines cut the Earth in half (mid-point is the Equator). Latitude lines measured in degrees start at 0 at Equator. In the Northern Hemisphere, the degree range is 0 (Equator) to 90 (North Pole). In the Southern Hemisphere, the degree range is 0 at the Equator to -90 (South Pole).


# Planning a future vacation - where to go?

![heatmap](Images/heatmap.png)
![hotel map](Images/hotel_map.png)

>Based upon the random sample of cities and the charts prepared in this assignment:
	1. Temps are highest at latitudes of -20 to 20 - close to the equator. This may be due to the fact that the equator receives direct light and the poles receive slanted light.
	2. Temperatures decrease as you move away from the Equator (latitude 0) and, similarly increase as you move closer to the Equator (latitude 0).
	3. I did not see a correlation between humidity, cloudiness and/or windspeed with latitude.


- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.

