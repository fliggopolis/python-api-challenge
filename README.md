# python-api-challenge
Module 6 Assignment

WeatherPy

In this project, latitude and longitude coordinates were randomly generated for 1500 different locations. The nearest city to easch location, wes added to a list of 602 uique cities. Utilizing Open Weather API temperature, cloudiness, humnidity and wind data was stored for each city. 

Utilizing linear regression these data points were compared to latitude. Only temperature had a strong correlation to latitude with temperature increasing as latitude approaches 0. None of the points had a meaningful correlation. 


VacationPy

Utilizing the previous city dataset, a global map was generated expressing each city as a point kon the map with it's corresponding weather data. Utilizing several 'ideal' weather parameters, the city list was filtered down and the Geoapify API was then used to find the nearest hotel to the city center for each of the remaining cities. 
