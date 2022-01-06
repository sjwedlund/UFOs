# UFOs

## Overview of the Analysis
The purpose of this analysis is to create a webpage using the data.js file of UFO sightings, that allows users to filter for multiple criteria at the same time. Using Javascript and HTML, table filters for the date, city, state, country, and shape have been added. 

## Results
To perform a search, start by entering a date in MM/DD/YYYY format. All sightings from the data.js file on that date will load.  
<img width="1680" alt="Screen Shot 2021-09-12 at 3 52 42 PM" src="https://user-images.githubusercontent.com/85920136/133005317-e0dc9132-50ab-4f9e-b25a-959ef47e8a58.png">
Or, enter a city. The page will need to be refreshed in order to start a new search, or the old search term must be deleted. 
<img width="1680" alt="Screen Shot 2021-09-12 at 3 59 29 PM" src="https://user-images.githubusercontent.com/85920136/133005431-e6064844-f72a-4e1d-8fb5-ee39520741f9.png">
The page is also designed to receive input from more than one field at a time. For example, the date and city have been input. Here is the result: 
<img width="1680" alt="Screen Shot 2021-09-12 at 4 01 00 PM" src="https://user-images.githubusercontent.com/85920136/133005461-1447bd8d-6a39-4c6d-9bc8-e3b142592dae.png">

## Summary
A drawback is that the cities, states, and countries in the data file have been recorded in lower case. If a person capitalizes the city or state name as it should be, the results won't populate, because it is case sensitive. 
One recommendation for further development by would be to change the case sensitivity of input in the city field in order to return results, because cities are supposed to be capitalized. The other recommendation would be to change the case sensitivity of the state field for the same reason. 
