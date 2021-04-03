# World_Weather_Analysis

## Summary
Using the Citipy and Pandas libraries alongside OpenWeatherMap's API to feed data to Google Maps' API.

## /Weather_Database 
* Created a randomized list of Latitude and Longitude coordinates
* Turned those coordinates into City Names and Country Codes via Citipy
* Used those City Names to call OpenWeatherMap's API and create a DataFrame with the results
* Saved DataFrame to .CSV

## /Vacation_Search 
* Loaded the .CSV File from the Weather_Database folder as a DataFrame
* Filtered the DataFrame by a temperature range and saved as a new .CSV file
* Using Google Directions API, added a column with the first Hotel Name result by iterating through each City in the DataFrame
* Plotted the Cities on a Google Maps figure with pop up boxes containing the Hotel Information

## /Vacation_Itinerary
* Loaded the .CSV File fromthe Vacation_Search folder as a DataFrame
* Used Google Maps API to search and display driving directions between 4 manually chosen cities.
