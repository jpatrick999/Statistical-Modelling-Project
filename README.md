# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Overall, the project aims to utilize data from various sources to gain insights into bike sharing patterns, local businesses, and points of interest in a selected city. It involves data collection, analysis, visualization, and modeling to achieve its objectives.

## Process
Part 1: Connecting to CityBikes API
Understand the structure and data provided by the CityBikes API.
Retrieve information about bike stations in a selected city.
Gather data on the number of available bikes and their geographical locations.

Part 2: Connecting to Foursquare and Yelp APIs
Connect to both Foursquare and Yelp APIs to gather data on local businesses and points of interest.
For each bike station obtained in Part 1, query the Foursquare and Yelp APIs to retrieve information about nearby restaurants, bars, and other points of interest.
Compare the quality and coverage of information provided by both APIs.

Part 3: Joining Data
Combine the data collected from the CityBikes API with the data from Foursquare and Yelp APIs.
Perform data visualization to explore relationships between bike stations and nearby businesses/POIs.
Store the collected data in an SQLite database.

Part 4: Building a Model
Build a regression model using statistical techniques to understand the relationship between the number of bikes in a location and the characteristics of nearby POIs.
Interpret the results of the regression model and derive insights into how local businesses and points of interest may impact bike usage in different areas

## Results
(fill in what you found about the comparative quality of API coverage in your chosen area and the results of your model.)

I found out that the API Coverage for YELP is much more robust and informative as compared to Foursquare. Both show good information, however, YELP has:

more information
more details

## Challenges 
(discuss challenges you faced in the project)

The biggest challenge was, and where I spent most time, was on the API query section. I had a lot of difficulty sending out queries to get the right behaviour (and data packages) from all 3 of the APIs.

Limitations of free API usage - had to wait min 24 hours for request limit to reset.

Very Limited API requests (Have to write complete code as to not run out of request)


## Future Goals
(what would you do if you had more time?)
Optimize API queries and data retrieval processes for efficiency and scalability.

Develop interactive dashboards or web applications to visualize the findings and insights in an accessible and user-friendly manner.

Experiment with more sophisticated modeling techniques beyond simple regression

Conduct further data cleaning and preprocessing to handle missing values, outliers, and inconsistencies, ensuring the robustness and accuracy of the analysis.
