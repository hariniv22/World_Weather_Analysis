# World_Weather_Analysis
# Overview

Using random function, we generate a set of 2,000 random latitudes and longitudes, and use citipy to retrieve the nearest city. Then we perform an API call with the OpenWeatherMap to gather city weather data such as 

 - Latitude and longitude
 - Maximum temperature
 - Percent humidity
 - Percent cloudiness
 - Wind speed and 
 - Weather description for each city. 
Then, we create a new DataFrame containing the updated weather data.
 
We use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.
 
Finally, using the Google Maps Directions API, we will create a travel route between the four cities as well as a marker layer map.
