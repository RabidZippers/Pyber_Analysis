# Pyber_Analysis

## Overview
Ridesharing services are growing every year. These services beneficial for riders and drivers. A market analysis was conducted to understand this market, and to help companies understand the behavior of customers and the economic trends. PyBer is a ridesharing company and this analysis is conducted using their rideshare data. 

### Purpose
The purpose of this analysis is to not only understand ridesharing in the 3 types of cities (urban, suburban, and rural), but to evaluate the correlation between the number of riders and drivers by the city type and its impact on fares. The overall analysis and visualizations, of data from the first quarter of 2019, will show how PyBer can possibly expand access and affordability to the ridesharing services. 

### Resources Utilized to Complete Analysis
* **CSV Files:** 
[city_data.csv](https://github.com/RabidZippers/Pyber_Analysis/blob/main/Resources/city_data.csv), 
[ride_data.csv](https://github.com/RabidZippers/Pyber_Analysis/blob/main/Resources/ride_data.csv)
* **Jupyter Notebook Files:**: 
[PyBer.ipynb](https://github.com/RabidZippers/Pyber_Analysis/blob/main/PyBer.ipynb), 
[PyBer_Challenge.ipynb](https://github.com/RabidZippers/Pyber_Analysis/blob/main/PyBer_Challenge.ipynb)
* **Python**: 
Python v3.7.6
## Results

### Overview of City Types
The bubble chart below shows the relationship between city types (urban, suburban, rural) and the total number of rides per city, the total number of drivers per city and the average fare (USD $) per city. The circle size correlates with driver count per city.

![Fig1](https://github.com/RabidZippers/Pyber_Analysis/blob/main/Analysis/Fig1.png)

### Ride Counts by City Type

Ride counts by city type is expressed using a box-and-whisker plot and a pie chart. The box-and-whisker plot shows that the urban ride count data includes an outlier with 39 rides in one city. In rural cities, the average number of rides is approximately 4 times lower than urban cities and 3.5 times lower than suburban cities. The pie chart conveys similar information, with each pie wedge representing a city and the percentage of its total rides. Urban cities have the highest percentage of total rides with 68.4% of rides, whereas suburban cities have 26.3% total rides and rural cities have 5.3%

![Fig2](https://github.com/RabidZippers/Pyber_Analysis/blob/main/Analysis/Fig2.png)
![Fig6](https://github.com/RabidZippers/Pyber_Analysis/blob/main/Analysis/Fig6.png)

### Driver Counts by City Type
Driver counts by city type is shown through the number of drivers per city type and the percentage of total drivers by city type. The pie chart shows that urban cities have the highest percentage of total drivers with 68.4% of rides, whereas suburban cities have 26.3% total drivers and rural cities have 5.3%

![Fig7](https://github.com/RabidZippers/Pyber_Analysis/blob/main/Analysis/Fig7.png)

### Fare Counts by City Type
Fare counts by city type is visualized through the number of fares per city type, the percentage of total fares by city type and the total weekly fares for each city type. The multiple-line graph shows total weekly fares for each of the city types. Overall, urban cities have the highest revenue in comparison to suburban and rural cities. Riders are most concentrated in dense urban areas, so this could explain why the sum of the fares for each week in urban areas is highest. Interestingly, fares proportionally increased across city type in the second half of February. 

![PyBer_Fare_Summary](https://github.com/RabidZippers/Pyber_Analysis/blob/main/Analysis/PyBer_fare_summary.png) 

## Summary
Based on the results, the following recommendations can be made to address difference found among the city types.
1.	The analysis could further benefit from having additional data points that span throughout the year, instead of focusing on the first quarter of the year. Additional data could provide insights into yearly trends and can be used to forecast ride, driver and fare counts for the future.  
2.	Conducting an analysis on the usage and demographics (e.g. age, gender) of the riders could provide further visualizations for the future, as well for allowing the marketing to be targeted to a specific demographic.
3.	Offering incentives to maintain loyal customers and employees, as well as attract new ones, will help drive this business and strengthen its relationship with existing customers and employees. 
