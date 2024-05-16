# python-api-challenge

In this challenge, I used Python to fetch weather data from a chosen API based on geographic coordinates, analyzed the data to understand equatorial weather patterns, and generated map plots to visualize the results.

Background

Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

In exploring the relationship between weather patterns and proximity to the equator in Part 1 of the assignment, the analysis revealed a strong correlation between temperature and latitude, as evidenced by linear regression plots. Surprisingly, there was a lack of significant relationship between humidity, cloudiness, wind speed, and latitude. These findings suggest potential avenues for further analysis to gain deeper insights into these weather phenomena.

In completing Part 2 of the assignment, I followed the requirements to create a map displaying points for every city in the city_data_df DataFrame. Additionally, I narrowed down the city_data_df DataFrame to find cities that met my ideal weather conditions. Although the criteria did not generate any searches for hotels using the Geoapify API, I proceeded to create a new column titled 'Hotel name' in the city data frame. This column was populated with 'No hotel found' for the cities that did not have any hotels meeting the criteria within 10,000 meters of the coordinates. Finally, I mapped the cities on the map with the additional information indicating 'No hotel found' in the hover message, providing a comprehensive visualization of the cities meeting the weather conditions but lacking nearby hotels.
