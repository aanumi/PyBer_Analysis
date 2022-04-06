# WRITTEN ANALYSIS: PYBER

## OVERVIEW
The purpose of the challenge is to create visualizations of rideshare data by city for PyBer by conducting an analysis that'll help improve access to ride-sharing services, and determine affordability for underserved neighborhoods. Datasets containing city and ride data are used to perform calculations to get total number of rides by city, driver, and sum of fares. Other functions were used to get the average fares per ride and driver for each city. New data frames were also created, with the project ending with a chart created to show at a glance, Total fare by city type for select months.

## RESULTS
### SUMMARY DATAFRAME
From the image below, key metrics were calculated to get total rides, drivers, and sum of fares by city type. A quick glance at the results reveal the following:

<img width="639" alt="Screen Shot 2022-04-06 at 1 46 59 PM" src="https://user-images.githubusercontent.com/100884241/162037716-e4aa5ef8-34f7-4bb8-af5f-95e05223ceab.png">

1. Urban cities had the highest number of rides, drivers, and sum of fares amongst all cities. This accounts for about 68.4% of all rides, 80.9% of all drivers, and approximately 62.7% of total fares. 
2. The rest of the distribution is split between Rural and Suburban cities, with Rural cities having the least share in rides, drivers, and total fares. Urban cities therefore contribute the most revenue, according to the data and calculations performed. 
3. An analysis of the average fares per ride and per driver however paint a different picture as we see that Rural cities have the highest average fares per ride ($34.62), and average fares per drivers ($55.49)

### TOTAL FARE BY CITY TYPE
We also used Matplotlib to create a multiple line chart to better help us visualize the results. The chart below shows Total Fare by City Type from January 1 2019 to April 29 2019. The chart shows a clear positioning of Urban cities having the highest fares for the select time period, with Rural cities showing the least amount of fares. A noticeable spike is also seen for all cities for the 3rd week of February in which they all have the highest fares respectively. The beginning of January and the end of April also shows a noticeable decline in fares for all city types.

![PyBer_fare_summary](https://user-images.githubusercontent.com/100884241/162038201-14d71cc1-8983-4373-8267-34b32deb45a2.png)

## SUMMARY
Three business recommendations to the CEO for addressing disparities among city types are discussed below:
•	Urban cities show the highest number of drivers, rides, and sum of fares as shown in the results and chart. If the CEO were evaluating strategic alternatives, there would be a great opportunity in the urban cities for greater investments as they are most lucrative. They have the best metrics of all city types, and greater profits can be realized if more investments were made in the urban regions.
•	Another great opportunity presents itself at the end of February, as we see in the chart that all city types had an increase in fares. More research or attention should be paid to that time period as it’s possible that a national event is the reason for increased fares in all city types at the end of February. PyBer could position itself to rake in more revenue by studying the reason for the increase, creating awareness through ads and marketing, and capitalizing on the increased awareness to rake in higher revenue.
•	Since one of the purposes of this project is to determine affordability for underserved neighborhoods, PyBer could look into reducing the cost of rides in both Suburban and Rural city types to encourage more users to use its ride-share services. PyBer should closely monitor the results of that strategy to see if it has a direct impact on increased rides, fares, and drivers. 
