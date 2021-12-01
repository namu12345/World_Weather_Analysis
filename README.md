# World Weather Analysis

## Overview
This analysis looks at different weather patterns around the global and offers insights to travelers who want to book a trip. Beta testers for the fictional app "PlanMyTrip" gave positive reviews, but recommended a few changes to enhance the app. Suggestions included adding the weather description to the weather data and use input statements to filter data for weather preferences. This will be used to identify potential travel destinations and nearby hotels. This new feature will also allow users to choose cities to create their travel itinerary.

## Resources
Jupyter Notebook
Python v3.7.x

- Dependencies:
    - pandas
    - requests
    - gmaps
    - numpy
- APIs:
    - OpenWeatherMap
    - Google Places
    - Google Maps JavaScript
    - Google Directions

## Results :

There are three folders here that offer different levels of analysis: weather database, vacation search, and vacation itinerary.

## Weather Database
This folder uses Open Weather Map API to pull weather information on over 724 different cities around the world. That information consists of:

- Maximum Temperature
- Cloudiness
- Wind Speed
- Humidity
- Current Weather Description

![image](https://user-images.githubusercontent.com/92283185/144169420-71211835-3fe0-41ce-b765-7ced579d7cf7.png)


These different categories of information make it easy for travelers to choose exactly what they are looking for in a travel destination.

## Vacation Search
This folder takes the information gained in the weather database and uses Google Maps API to plot different travel destinations with a hotel at each location. For example, the image below shows the locations of all the places in the database that have an daily maximum temperature between 68 and 75 degrees farinheit.

<img width="725" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/92283185/144168651-92c2be33-b338-48f3-a8ff-459603ea859c.PNG">

## Vacation Itinerary
This folder takes the search information from the search folder and uses Google Maps directions API to create a vacation itinerary. For example, the image below shows a 4 stop itinerary in Australia that features Yulara, Blackwater, Coolum Beach and Byron Bay.

<img width="727" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/92283185/144169073-c76b5820-83cc-43d3-ab2e-d021dda6bea0.PNG">

And then created marker layer map of the cities on the travel route.

<img width="733" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/92283185/144168987-f94f5d41-6c32-47a1-b8f0-497b20e48117.PNG">


