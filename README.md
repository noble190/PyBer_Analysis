# PyBer_Analysis

## Overview
<hr>

The purpose of this analysis has been to study ride sharing data from a number of municipalities split into three categories: Urban, Suburban, and Rural. Through the use of DataFrames and visualizations, we are able to examine the patterns in the data as they manifest across the municipality types, and utilize the data in support of decisions.

## Results
<hr>

With Pandas, we were able to use groupby together with aggregate functions to summarize the ride sharing data and reveal patterns.

### Summary Data:
![Ride sharing data summary](https://github.com/noble190/PyBer_Analysis/blob/main/Resources/pyber_summary.png)

### Total Rides
The data shows that intuitively, the total number of rides is positively correlated with population density.

### Total Drivers
As expected, the data shows a positive correlation between population density and the total number of drivers. Taken in combination with Total Rides, we can see that Rural areas have approximately 2 rides for each driver, Suburban areas have approximately even numbers of rides and drivers, and Urban areas have more drivers than rides.

### Total Fares
The Total Fares metric increases with population density. This metric is immediately related to Total Rides, and both increase relatively proportionally.

### Average Fare per Ride
The data shows that there is a slight negative correlation between population density and Average Fare per Ride. This may be explained by the higher likelihood of shorter trips in more densely populated areas. There is also a likely fixed cost component to each fare, which would mitigate the impact of trip length on the total fare, explaining the smaller correlation than intuitively expected.

### Average Fare per Driver
Average Fare per Driver is a function of Total Fares and Total Drivers. As expected, areas where rides outnumber drivers see drivers earning more than the average fare per ride, and vice versa. 


### Data by Month:
![Ride sharing data by month](https://github.com/noble190/PyBer_Analysis/blob/main/analysis/totalFareByCityType.png)


## Summary
<hr>
Based on the data, we can make three recommendations to the CEO:

1. Rural (and to a lesser extent, Suburban) areas are underserved with regard to available drivers. A smaller driver pool would likely result in more waiting time and less options available for riders, which would discourage ridership. Perhaps financial incentives may be offered to Urban drivers to shift them to underserved areas.

2. 






Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.
