# PyBer Analysis of 2019 Rideshare Data

## Overview of Analysis
The CEO of PyBer, V. Isuualize, requested an analysis of the company's ride-share data starting in January through early May of the year 2019. This data will be used to help improve access to ride-sharing services and determine affordability for underserved neighborhoods.

To help with the visualizations, this project used Matplotlib and Jupyter Notebook to the charts that are used in this analysis. The charts presented show the various relationships between city types and other data such as the number of riders, drivers, and fares.


The results of the analyis will be covered first followed by a summary of recommendations based on the results of this analysis.

## Results

There are 3 distinct city types included in PyBer's data: Urban, Suburban, and Rural. The datasets from these different types of cities vary greatly when comparing one against the other. This section contains several charts showing these relationships in a concise, clear manner.

The results are divided into the following sections to show the differences between the 3 differenty city types for these Ride-sharing metrics:
- Total Rides
- Total Drivers
- Total Fares
- Average Fare per Ride and Driver
- Total Fare

Before analysis, the 2 input files, city_data.csv and ride_data.csv were read in and merged to create a simple dataframe to analyize various stats such as Total Drivers and sum of all Fares for each city type.  Later this data was used to create more complicated relationships to get a better understanding of how the stats were affected by the different types of cities to present a multi-line graph entitled "Total Fare by City Type".

The Pyber Summary dataframe can be seen here: 

<img src="./Resources/pyber_summary_df.jpeg" alt="Pyber Summary DF" width="600"/>

From the above image we can see the number of Total Rides and Total Drivers, the Sum of all the Fares, the Average Fare per Ride and the Average Fare per Driver. The values for these metrics have been broken down into 3 categories based on the type of city Rural, Suburban and Urban. 

### Total Rides

The following table shows the breakdown for total rides by city type:
| City Type | Total Rides |
|-----------|-------------|
| Rural     |     125     |
| Suburban  |     625     |
| Urban     |   1,625     |

A rough calculation shows that rural cities had less than a tenth of the number of rides as urban areas and less than a fifth of the rides of suburban cities. Even suburban areas have less than half the number of rides compared to urban areas.

Since rural areas have a lot less people spread out than more densely populated urban areas, 125 vs 1,1625 makes sense. In most rural areas almost everyone has their own car for transportation so it is also a lot less likely that someone is in need of transportation from an outside source.

Similar to rural areas, suburban cities also had a relatively low amount of riders than urban areas.

As we look at the total number of drivers and the total sum of the fares received in each type of city we will try to get a better idea of how Pyber can increase ridership in rural and suburban areas.

### Total Drivers

The following table shows the breakdown for total drivers by city type:
| City Type | Total Drivers |
|-----------|---------------|
| Rural     |        78     |
| Suburban  |       490     |
| Urban     |     2,405     |

Here a rough calculation shows that suburban cities have more than 5 times the number of drivers as rural cities and urban ones have over 25 times the number of drivers than urban ones.  Urban cities also have approximately 5 times the number of drivers than in the suburbs.

TODO: add more detail

### Total Fares

TODO: add table here with observations.

### Average Fare per Ride and Driver

TODO: add table here with observations.

### Total Fare by City Type

TODO: add Line Chart here with observations.

## Summary

### Recommendation 1
TODO: rec 1

### Recommendation 2
TODO: rec 2

### Recommendation 3
TODO: rec 3


