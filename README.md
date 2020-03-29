## WeatherPy

Here, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a [simple Python library](https://pypi.python.org/pypi/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.

I first build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

I then ran a linear regression on each relationship, and separated them into Northern Hemisphere and Southern Hemisphere:

* Northern Hemisphere - Temperature (F) vs. Latitude
![](Images/nmt.PNG)
* Southern Hemisphere - Temperature (F) vs. Latitude
![](Images/smt.PNG)
* Northern Hemisphere - Humidity (%) vs. Latitude
![](Images/nh.PNG)
* Southern Hemisphere - Humidity (%) vs. Latitude
![](Images/sh.PNG)
* Northern Hemisphere - Cloudiness (%) vs. Latitude
![](Images/nc.PNG)
* Southern Hemisphere - Cloudiness (%) vs. Latitude
![](Images/sc.PNG)
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
![](Images/nws.PNG)
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
![](Images/sws.PNG)