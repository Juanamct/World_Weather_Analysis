# World_Weather_Analysis

# Enhance the "PlanMyTrip" app with additional data, functionality, and customization
  * Weather description
  * Weather preference: Input statements to filter the data for weather preferences
    - This will be used to identify potential travel destinations and nearby hotels
  * Create a travel itinerary: Using Google Maps Directions, beta tester to able to choose four cities 
  
  
## Deliverable 1: Retrieved Weather Data:

### Generated a set of latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. In addition to the city weather data, retrieved the current weather description for each city. Created a new DataFrame containing the updated weather data.

    - Latitude and longitude
    - Maximum temperature
    - Percent humidity
    - Percent cloudiness
    - Wind speed
    - Weather description (for example, clouds, fog, light rain, clear sky)
    - Add the weather data to a new DataFrame
    
    
 ## Deliverable 2: Created a Customer Travel Destinations Map
 
 ### Used input statements to retrieve customer weather preferences. Using those preferences, identified potential travel destinations and nearby hotels, then showed those destinations on a marker layer map with pop-up markers.
      
    - Input statements written to prompt the customer for their minimum and maximum temperature preferences.
    - A new DataFrame created based on the minimum and maximum temperature, and empty rows dropped. 
    - The hotel name retrieved and added to the DataFrame, and the rows that don’t have a hotel name dropped. 
    - The DataFrame exported as a CSV file 
    - A marker layer map with pop-up markers for the cities in the vacation DataFrame created. Each marker has the following information: 
        * Hotel name
        * City
        * Country
        * Current weather description with the maximum temperature
      ![WeatherPy_vacation_map](https://user-images.githubusercontent.com/107228424/181078162-001cec76-998e-4d72-9095-3f6c51ad2aa0.png)


## Deliverable 3: Create a Travel Itinerary Map

### Using the Google Directions API, created a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, created a marker layer map with a pop-up marker for each city on the itinerary.
    
   - Four DataFrames created, one for each city on the itinerary. 
   - Latitude and longitude pairs for each of the four cities retrieved. 
   - A directions layer map between the cities and the travel map created 
   - A DataFrame containing the four cities on the itinerary created. 
   - A marker layer map with a pop-up marker for the cities on the itinerary created 
      Each marker has the following information: 
        * Hotel name
        * City
        * Country
        * Current weather description with the maximum temperature
        ![WeatherPy_travel_map](https://user-images.githubusercontent.com/107228424/181079628-13041686-c73c-45b2-86b5-59019daaeacb.png)
        ![WeatherPy_travel_map](https://user-images.githubusercontent.com/107228424/181079649-17bcef6d-3e04-4792-8e0c-c8d596309ffb.png)




