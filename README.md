# Python-API-Challenge

## WeatherPy
- Randomly select at least 500 unique non-repeat cities based on latitude and longitude
- Perform a weather check on each city using a series of successive API calls
- Include a print log of each city as it's being processed with city name and number
- Save a CSV of all retrieved data and PNG image for each scatter plot

Create a series of scatter plots to showcase the following relationships:
- Temperature (F) vs Latitude
- Humidity (%) vs Latitude
- Cloudiness (%) vs Latitude
- Wind Speed (mph) vs Latitude

Run linear regression on each relationship, separating the plots into Northern Hemisphere and Southern Hemisphere:
- Northern Hemisphere: Temperature (F) vs Latitude
- Southern Hemisphere: Temperaure (F) vs Latitude
- Northern Hemisphere: Humidity (%) vs Latitude
- Southern Hemisphere: Humidity (%) vs Latitude
- Northern Hemisphere: Cloudiness (%) vs Latitude
- Southern Hemisphere: Cloudiness (%) vs Latitude
- Northern Hemisphere: Wind Speed (mph) vs Latitude
- Southern Hemisphere: Wind Speed (mph) vs Latitude

## VacationPy
- Create a heat map that displays humidity for every city from WeatherPy
- Narrow down the DataFrame to find your ideal weather condition
- Use Google Places API to find the first hotel for each city located within 5000 meters of your coordinates
- Plot the hotels on top of the humidity heat map with each pin containing the hotel name, city, and country
