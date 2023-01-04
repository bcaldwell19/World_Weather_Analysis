# World_Weather_Analysis

 >PLANMYTRIP is a top travel technology company that specializes in internet-related services in the hotel and lodging industry. Jack is the head of analysis for the user interface team. He's asked you to help him collect and present data for customers via the search page, which they will then filter based on their preferred travel criteria in order to find their ideal hotel, anywhere in the world. As part of your analysis, you will need to perform statistical calculations on the data using linear regression on the weather parameters in the Northern and Southern hemispheres. This data will help your team predict the best time of year for people to plan their vacation. Finally, you will export the data, clean it, and use the weather data to choose the best cities for vacation based on certain weather criteria, and then map these cities using GeoViews and the GeoApify API. Are you ready to help travelers find their ideal vacation spot? If so, pack your suitcase and let's get started.

 >Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they've recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data.

 >For this challenge, you will use the weather description data you've already retrieved in this module to enhance the PlanMyTrip app. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. The beta tester will choose four cities from the list of potential travel destinations to create a travel itinerary. Finally, using the Geoapify Routing API, you will create a travel route between the four cities and a marker layer map.
_______________________________________________________________________________________________

In this repo, you will find three folders: 

1) **Weather_Database**: 

This folder contains a Jupyter Notebook using Python and the OpenWeatherMap API for weather. 
This file randomly generates random latitudes and longitudes, and this data is then sent to OpenWeatherMap API for weather information. 
_______________________________________________________________________________________________

2) **Vacation_Search**: 

This folder contains a Jupyter Notebook using Python and the Geoapify API for a hotel search using the generated csv file from the weather_database.
The user supplies a desired temperature range. The script uses this input to determine hotels in climates that match the customer's requirements. 
![](/Vacation_Search/WeatherPy_vacation_map.png)

_______________________________________________________________________________________________

3) **Vacation_Itinerary**: 

This foldercontains a Jupyter Notebook using Python and the Geoapify API for the route planner based on 4 selected vacation spots based on input from the customer in the vacation search file. 
![](/Vacation_Itinerary/WeatherPy_travel_map.png)
