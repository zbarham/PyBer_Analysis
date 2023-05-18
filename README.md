# PyBer Analysis Report

## Overview of the analysis

The purpose of this analysis is to use Pandas and Matplotlib to examine the disparities in ride-sharing data among different city types (Urban, Suburban, and Rural). This will provide insight for decision-makers at PyBer on how they can improve their services and address any potential issues. The analysis involves comparing metrics such as total rides, total drivers, total fares, average fare per ride, and average fare per driver for each city type.

## Results

![PyBer_summary_df](https://github.com/zbarham/PyBer_Analysis/blob/main/analysis/Challenge_5_Deliverable_1.png)

From the data, it is clear that there are significant disparities in ride-sharing metrics among the three city types:

1. **Urban** cities have the highest total number of rides (1,625) and drivers (2,405). These cities also generate the most total fares ($39,854.38), indicating that ride-sharing is most utilized in urban settings. However, the average fare per ride ($24.53) and the average fare per driver ($16.57) are the lowest among the three city types. This might be due to shorter trip distances in urban areas and the higher number of drivers, which could increase competition and drive down fares.

2. **Suburban** cities are in the middle ground. They have significantly fewer total rides (625) and drivers (490) than urban cities, but more than rural areas. The total fares from suburban cities ($19,356.33) are about half of that of urban cities, but substantially higher than rural areas. The average fare per ride ($30.97) and per driver ($39.50) are higher than in urban cities, which might indicate longer trip distances in suburban areas and less competition among drivers.

3. **Rural** cities have the lowest total number of rides (125) and drivers (78), reflecting the lower population density in these areas. However, they generate the highest average fare per ride ($34.62) and per driver ($55.49), potentially due to longer trip distances and less competition among drivers in rural areas.

![Total_Fare_by_City_Type](https://github.com/zbarham/PyBer_Analysis/blob/main/analysis/Total_Fare_by_City_Type.png)

## Summary

Based on the results of the analysis, the following three business recommendations can be made to address the disparities among city types:

1. **Increase marketing efforts in Rural and Suburban areas:** Given that rural and suburban areas command higher average fares per ride and driver, it might be beneficial to attract more riders in these areas. This could be done through targeted marketing campaigns or promotional offers to increase the visibility of PyBer's services and encourage more people to try out the service.

2. **Attract more drivers in Rural and Suburban areas:** There is a significantly lower number of drivers in these areas compared to urban cities, which could be limiting the number of rides and thus the total fares collected. By incentivizing more drivers to operate in these areas, PyBer could potentially increase its revenue. Incentives could include higher earnings per ride, bonuses for a certain number of rides, or subsidies for fuel or vehicle maintenance.

3. **Re-evaluate fare pricing in Urban areas:** The lower average fare per ride and driver in urban cities could be due to higher competition and shorter distances. PyBer might want to consider evaluating its pricing strategy in these areas. If it's possible to slightly increase fares without significantly impacting the demand, this could lead to higher revenue. Moreover, implementing a dynamic pricing model that takes into account factors such as demand, time of the day, or traffic situation could also help optimize fares and revenues.

By addressing these disparities, PyBer can ensure more equitable service across city types and potentially increase its revenue.
