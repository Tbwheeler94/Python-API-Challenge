# Python-API-Challenge

### In this repository you will find:

## Part I - WeatherPy:

The first half of this script visualizes the weather of 500+ cities across the world of varying distance from the equator using data from the OpenWeatherMap API.

I use scatter plots to visualize the relationships between:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

In the second half, run linear regressions on each relationship, only this time separating them #into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern #Hemisphere (less than 0 degrees latitude). Displayed plots include:

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

All plots are exported to PNG images.

## Part II - VacationPy:

The second half of this script uses weather data gathered from Part I to visualize and identify #ideal future vacation locations. I use jupyter-gmaps and the Google Places API for this part of #the assignment.

The first visualization is a heat map that displays the humidity for every city from the part I narrowed by the following parameters:

     -A max temperature lower than 80 degrees but higher than 70.
     -Wind speed less than 10 mph.
     -Zero cloudiness.

Using Google Places API I find the first hotel for each city located within 5000 meters of the output coordinates.


Finally, I plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
