# World_Weather_Analysis
Module 6


## Project Overview

PlanMyTrip looks at the weather around the world and offers insights to travelers who want to book a trip. There are three folders that offer different levels of analysis: weather database, vacation search, and vacation itinerary.

## Weather Database

Using Open Weather Map API, this folder includes the weather data (Max Temp, Cloudiness, Wind Speed, Humidity, weather description) for over 500 cities across the world.

## Vacation Search

In this folder, we create a customer travel destinations map using the information from Weather Database and Google Maps API to find different travel destinations with a hotel at each location. Taking user input, places with a certain range of temperature are shown in the map. For example, this map shows places that have a temperature between 70 and 90 degrees fahrenheit.

![alt text](https://github.com/JabboRamirez/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)

## Vacation Itinerary

In this folder, we use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. For example, the map shows a 4 stop itinerary in California: from Laguna, CA to Pacifica, CA to Half Moon Bay, CA to Pacific Grove, CA and back to Laguna, CA.

![alt text](https://github.com/JabboRamirez/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

Finally, we created a marker layer map with a pop-up marker for each city on the itinerary (Laguna, CA, Pacifica, CA, Half Moon Bay, CA, Pacific Grove, CA).

![alt text](https://github.com/JabboRamirez/World_Weather_Analysis/blob/main/Vacation_Search/vacationshearch.png)
