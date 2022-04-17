# Overview of WeatherPy

## Purpose

MyTrip is a travel technology company that is looking to add more features to its search functions.
The purpose of this project was to add more filtering options for customers planning
their vacations based on their weather and temperature preferences. Once their
preferred travel criteria is inputted, the resulting travel locations and suitable hotels are displayed
on Google Maps with pop-up markers displaying the city and weather information.

The city data was retrieved through the citypy module
and the weather data was retrieved through an API call from Open Weather Maps.
After beta-testing was performed, the code was revised to add a recommendation to
include the current weather description in the weather data. 


### Resources
* API Sources: Open Weather Map, Google Places
* Software: Jupyter Notebook 6.4.5, Python 3.7.11
* Python Libraries/Dependencies: Pandas library, Matplotlib library, Citipy, Gmaps, Request

### Project Overview

1. Collect the weather data for the randomly generated list of cities(based on latitude and longitude pairs)
through an API call from Open Weather map

2. Create a map with pop-up markers displaying the hotel name, city and weather information of the cities that matched
the preferred temperature range inputted by the customer.

3. Select 4 cities based on the previous filter to create a map displaying the travel route with each city as a stop.
Create a second map with pop-up markers displaying the hotel name, city and weather information of the 4 chosen travel
locations.
