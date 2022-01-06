# PlanMyTrip - Weather & Travel App
## Overview
The PlanMyTrip app was successful in beta testing, and is slated for the following updates:
* additional cities added
* user feature to filter for weather preference
* create trip itineraries with interactive map

## Deliverable 1
### Increase the coordinates database from 1,500 to 2,000 and include current weather description for each location.
Weather_Database.ipynb was refactored to increase the database size and add current weather description from the OpenWeather JSON, and then added to a new csv file (WeatherPy_Database.csv) to import into the trip itinerary code.

## Deliverable 2
### Use input statements to retrieve customer weather preference, and then use those preferences to identify potential travel destinations and nearby hotels.
The Vacation_Search.ipynb details how the csv from deliverable one was loaded into Vacation_Search.ipynb to create a preferred cities dataframe based on user input. gmaps was utilized to create the interactive maps, as seen below. The output of this code is stored as WeatherPy_vacation.csv.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/94259442/148438801-0495ffec-da60-4e40-b165-e996f435b8b5.png)

## Deliverable 3
### Use Google Directions API to create a travel itinerary that shows the route between selected cities.
Data from WeatherPy_vacation.csv was used in conjunction with Google Directions API to create travel itineraries for clients. An example can be seen below, were four cities in the same country were selected as a trip option. Full details of the code can be found in Vacation_Itinerary.ipynb.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/94259442/148439362-42f5ba1f-52ab-4396-9831-b83e69ba9f4a.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/94259442/148439392-0f66de00-0987-4e7c-8fbe-7d72054a2f6d.png)
