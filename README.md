# Pyber_analysis


## Overview of the analysis
The purpose of this analysis is to use ride-share data from the company Pyber to compare key ride-share metrics by city type. The analysis will be used to generate data-driven insights and recommendations to the CEO of pyber in order to improve accessbility and affordability to its customers. 

## Results
The analysis was conducted in a python jupyter notebook and can be found here: [Analysis Script](https://github.com/fadlnabbouh/pyber_analysis/blob/main/PyBer_Challenge.ipynb). 

To determine the differences in ride sharing data across different city types, a summary dataframe was generated with the total rides, drivers, and fares by city types, as well as the average fare per ride and driver by city type.
![summary dataframe](https://github.com/fadlnabbouh/pyber_analysis/blob/main/Resources/pyber_summary.png).

In the above data frame, it is clear that the total number of rides is highest in urban cities and lowest in rural cities. This trend also exists with total drivers and total fares. This trend is negatively correlated with average fare per ride and average fare per driver, where the highest occurs in rural cities while the lowest occurs in urban cities. This trend is likely to occur because rural areas may require further travel distance, increasing the fare. In addition, with fewer drivers in rural areas, fares become higher due to having a lower supply to demand ratio.

A multi-line chart was also generated to show the total amount of fare by city type over time in January to April of 2019. 
![line chart](https://github.com/fadlnabbouh/pyber_analysis/blob/main/analysis/PyBer_fare_summary.png)

In this line chart, it is clear that the urban cities consistently generate the most total fare while rural generates the least. In addition, the multi-line chart displays the demand for drivers over time, indicated by an increase in total fares. The trend seems to be similar across all three cities, although suburban areas have a large increase around the end of April relative to the other two cities. In addition, all cities seem to have spikes around the end of February/ Early March. Urban cities also have large fluctuations during March, whereas the other two city types are more consistent. 

## Summary

Based on the above results, I'd make the following recommendations to the CEO of Pyber: 
1. Because there is a trend whereby more drivers = more total fares but a decrease in average fare per ride, the company may consider allocating more drivers to rural cities (or creating incentives for drivers to work in rural cities). This would not only increase the supply of drivers in these cities, but it would make ride sharing more affordable and accessible to these communities, potentially generating more profits. 
2. Pyber may also consider a discount by distance initiative. It is clear that the average fare per ride and per driver is much higher in rural cities than in urban cities. Suburban cities are also much higher than urban cities as well. This may be due to lower demand of drivers, but also because of longer distances. Urban drivers would need to drive more often and drive more customers than other cities because their short distances do not fulfill a livable wage. On the contrary, rural area drivers become more expensive and less accessible/affordable, decreasing the amount of potential money they could make. To improve this, Pyber should consider increasing its base fare for shorter distances, and having the cost of a ride increase at a slower rate. This way, longer drives arent as expensive, increasing the number affordability of ride share in rural areas. It will also close the gap in terms of average fare per ride and average fare per driver between urban and rural areas (increase urban while decreasing rural). 
3. Using the multi-line chart, the CEO may gain insight into then demand is highest for drivers and when it is lowest. By understanding these insights, Pyber can allocate more drivers in high demand times, as well as increase fares, to optimize profits. For example, suburban areas have a spike in demand and usage of ride share around the end of April. It would benefit Pyber to allocate more drivers to these cities around that time, lowering the average fare and increasing profits by making ride share more accessible and affordable.   
