# PyBer_Analysis

Using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. Submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.
# Overview:
The project goal was to analyze all the rideshare data from January to early May of 2019 and create compelling visualizations comparing the city types, urban, suburban, and rural.

## Deliverables:
Fig 1. is a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban in coral, suburban in light blue, and rural in gold. ![Fig 1.](https://github.com/vvinci21/PyBer_Analysis/blob/main/analysis/Fig1.png)

### Descriptive statistics:
The total number of rides for each city type.
* The mean ride count for urban cities is 24.62, for suburban cities is 17.36, and for rural cities is 6.94.
* The median ride count for urban cities is 24, for suburban cities is 17, and for rural cities is 6.
* The mode for ride counts in urban cities is 22 and occurs 7 times, for suburban cities is 17 and occurs 7 times, and for rural cities is 6 and occurs 5 times.

The average fares for each city type.
* The mean fare price for urban trips is $24.53, for suburban trips is $30.97, and for rural trips is $34.62.
* The median fare price for urban trips is $24.64, for suburban trips is $30.75, and for rural trips is $37.05.
* The mode fare price for urban trips is $22.86 and occurs 5 times, for suburban trips is $17.99 and occurs 3 times, and for rural trips is $37.05 and occurs 2 times.

The total number of drivers for each city type.
* The mean driver count for urban cities is 36.678, for suburban cities is 13.712, and for rural cities is 4.296.
* The median driver count for urban cities is 37, for suburban cities is 16, and for rural cities is 4.
* The mode driver count for urban cities is 39 and occurs 86 times, for suburban cities is 20 and occurs 79 times, and for rural cities is 1 and occurs 32 times.

### Box-and-Whisker Plots:
* The number of rides for each city type are seen in Fig 2.
    ![Fig 2.](https://github.com/vvinci21/PyBer_Analysis/blob/main/analysis/Fig2.png)
    * An outlier was identified in the urban city.
* The fares for each city type are seen in Fig 3.
    ![Fig 3.](https://github.com/vvinci21/PyBer_Analysis/blob/main/analysis/Fig3.png)
* The number of drivers for each city type are seen in Fig 4.
    ![Fig 4.](https://github.com/vvinci21/PyBer_Analysis/blob/main/analysis/Fig4.png)

### Pie Charts:
* Fig 5 is the percent of total fares. 
    ![Fig 5.](https://github.com/vvinci21/PyBer_Analysis/blob/main/analysis/Fig5.png)
* Fig 6 is the percent of total rides.
    ![Fig 6.](https://github.com/vvinci21/PyBer_Analysis/blob/main/analysis/Fig6.png)
* Fig 7 is the percent of total drivers.
    ![Fig 7.](https://github.com/vvinci21/PyBer_Analysis/blob/main/analysis/Fig7.png)

# Analysis:
The goal is to analyze the total weekly fare data to summarize how city types differ. These differences will be used to impact the decisions at Pyber.

## Results: 
![Total Fare by City Type](https://github.com/vvinci21/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
Total fares seem to increase as the seasons change from winter to spring. There is also an increase in total fares for the city types during the spring holidays.
The main difference between the ride-share data for each city type is volume. Urban cities have the most drivers, rides, and total fares. Suburban cities have less than half of the total rides and even less the number of drivers than urban cities. However, suburban cities still earn around half of the total fares that of urban cities. The average fare earned per suburban driver is double the average fare made per driver in urban cities. Rural cities have the lowest rides, drivers, and total fare, but the average fare per ride and driver is the highest. This demonstrates supply and demands relationship to the fares. 

## Summary: 
Based on the results of the summary, here are three recommendations to increase earnings.
* For urban cities, the amount of drivers is greater than the number of rides. Having less drivers will increase the average fare earned per driver.
* For suburban cities, the number of rides is greater than the number of drivers. More drivers may increase the number of rides and the number of fares earned to meet demand.
* The business case for rural cities is less appealing as more people own cars and are less likely to require ride sharing. Locations in rural cities are also more spread out and further apart leading to higher ride share prices. 
