# World_Weather_Analysis

## Overview of the project

### Purpose of the analysis

In this analysis, we examined different weather patterns for a hypothetical weather company, PlanMyTrip. This analysis was aimed at helping travellers who want to book a trip in cities aroung the world. Description was added to weather data retrieved in the module while input statements were used to filter weather data in order to identify potential travel destinations and nearby hotels. Google Maps Directions API was used to create travel route between four Austalian cities - Carnarvon, Port Keats, Mount Isa and Yulara.


### Summary

#### Weather Database

A list of 200 random latitudes and longitudes was created to get the rearest cities.

API call was performed and information retrieve based on latitude and longitude, maximum temperature, percent humidity, percent cloudiness, wind speed and weather description and the data added to a DataFrame before it was saved as a CSV file.

#### Vacation Search

This section consolidates on the weather database by applying information gained to Google Maps API in plotting several destinations comprising different hotels. This can be seen in the diagram below.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/91093413/140644849-7b968bc1-312e-4c69-b9bd-77818e063b6a.png)

#### Vacation Itinerary

Vacation itinerary is created using 4 stops in Australian cities. These cities are: Carnarvon, Port Keats, Mount Isa and Yulara.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/91093413/140645162-ef53c029-ee6f-4e02-9959-20611574ea03.png)


The addition of markers as well as available hotels is represented in the table below.

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/91093413/140645095-8ec78747-c41e-4ac0-a9b2-184ee35aff8c.png)




