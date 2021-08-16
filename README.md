# SurfsUp-Challenge
Climate analysis in Python and SQLite.

## Overview
This analysis uses SQLite queries to collect data from a Hawaii climate database in order to inform the decision of where to open an ice cream and surf shop. This challenge focuses on the weather in the months of June and December in order to assess which months of the year would be best suited for the shop's operations in terms of the weather conditions. 

## Results
The table below summarizes the data for temperatures in June.
![June](/Users/simon/Desktop/DS_Classwork/SurfsUp-Challenge/Resources/June.png)

The table below summarizes the data for temperatures in December.
![December](/Users/simon/Desktop/DS_Classwork/SurfsUp-Challenge/Resources/December.png)

Based on these results, we come up with the following takeaways:
* The variation in temperature between June and December is not very large. The average in June is 75 and in December it is 71, not much lower. 
* The maximum recorded temperature in June is 85 and the maximum in December is 83, again not much lower. 
* On the other hand, the minimum recorded temperatures do show more of a differential, from 64 in June to 56 in December. This may indicate that in December there could be some days where the ice cream shop would not receive many customers because of the temerpature, since 56 degrees is not ideal weather for ice cream nor for surfing.

## Summary
Overall, the temperature in Hawaii varies very little, with average temperatures in June in December varying only by a few degrees. By running two additional queries that output summary statistics for the precipitation levels in June and December (shown in the code), we see that precipitation levels are higher in December than in June. Therefore, the midyear months will definitely allow for better business. Another additional query we could run would be to further strip down the data by selecting specific stations that are closest to the propective shop location, which would yield the most reliable results as these stations would give the most accurate representation of the weather conditions at the shop location.
