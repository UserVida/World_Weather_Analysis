# Overview of Project - WeatherPy

## Purpose
MyTrip is a travel technology company that is looking to add more features to its search functions. The purpose of this project was to add more filtering options for customers planning their vacations based on their weather and temperature preferences. Once their preferred travel criteria is inputted, the resulting travel locations and suitable hotels are displayed on Google Maps with pop-up markers displaying the city and weather information.

The city data was retrieved through the citypy module and the weather data was retrieved through an API call from Open Weather Maps. After beta-testing was performed, the code was revised to add a recommendation to include the current weather description in the weather data.

## Technologies used:
API Sources: Open Weather Map, Google Places
Software: Jupyter Notebook 6.4.5, Python 3.7.11
Python Libraries/Dependencies: Pandas library, Matplotlib library, Citipy, Gmaps, Request

## Results 
The weather data was collected to randomly generate a list of cities (based on latitude and longitude pairs) through an API call from Open Weather map

A map was created with pop-up markers displaying the hotel name, city and weather information of the cities that matched the preferred temperature range inputted by the customer.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/97644424/204120734-0069d904-76d7-43de-9326-8c9406af34bb.png)


Four cities were selected based on the previous filter to create a map displaying the travel route with each city as a stop. A second map was created with pop-up markers displaying the hotel name, city and weather information of the 4 chosen travel locations.

<img width="960" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/97644424/204120756-4e7628a2-fb6d-404b-b1e2-78603d4e5a4c.png">

### Authors
•	Zainab Cheentavida