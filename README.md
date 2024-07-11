In this Module I worked with two APIs (Application Programming Interface), to find and analyse weather related 
relationships, while simultaniusly using this information in real world application to find ideal places to visit 
based on user bias. 

In Weatherpy the primary focus has been on understanding how different weather parameters such as temperature, humidity, cloudiness, and wind speed vary with latitude. We saw how some of these interactions are clearly statiscally 
significant, while others are not. Specifically, we created a linear regression equation that we could apply to each 
interactions, in order to get a p-values and r-values. Visualizing the slope and direction of our data gives a simpler
understanding of what exactly is going on in this relationship, and whether we can confirm or reject the null hypothesis.
We saw that our our most significat relationship was between Latitude vs. Humidity. In the Nothern Hemisphere as latiude increases Temperature decreases. In the Southern Hemisphere, as Latitude increases Temperature also increases since its moving towards the equator. 
From this data I created a csv file, with city information from all accross the world to help find ideal places to go on vacation. Using this data, we narrowed down our ideal weather conditions, which I then used to zoom in on several cities that fit this criteria. 

Next we used Geopify API, to gather real time information on potential Hotels in the radius we wanted within each city. This gave us Hotel suggestions that fit the criteria, and then were able to neatly map and present a synthesized and personalized map of ideal cities, with Hotel suggestions. Making this an excellent way to find personalized data based on user or company preference. 

For this Module assignment, I used past class activities, Student Xpert AI, and ChatGpt, to generate, construst and ammend synthax and logic. 
