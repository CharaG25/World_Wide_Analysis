# World_Wide_Analysis
 use pseudocode to map out

do the following:

Import our dependencies and initialize counters and an empty list that will hold the weather data.
Loop through the cities list.
Group the cities in sets of 50 to log the process as we find the weather data for each city.
Two counters will be needed here: one to log the city count from 1 to 50, and another for the sets.
Build the city_url or endpoint for each city.
Log the URL and the record and set numbers.
Make an API request for each city.
Parse the JSON weather data for the following:
City, country, and date
Latitude and longitude
Maximum temperature
Humidity
Cloudiness
Wind speed
Add the data to a list in a dictionary format and then convert the list to a DataFrame.
