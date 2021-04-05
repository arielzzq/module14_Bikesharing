# An Analysis on CitiBike Data in NYC in August

## Overview of the analysis
The purpose of this analysis is to show the user habit, and operating situation of bike-sharing business in New York City.

## Results
[link to dashboard](https://public.tableau.com/profile/ziqin.zhu#!/vizhome/Challenge_16174206363420/Story1?publish=yes)

The link above is the Tableau story for this analysis. There were 2344224 rides in total in August.

![Number_of_Rides](/Images/Number_of_Rides.png)

Among all rides, 1900359 rides were made by subscribers and 443865 were made by customers.
![Customer_Number](/Images/Customer_Number.png)
![Subscriber_Number](/Images/Subscriber_Number.png)

The trip duration for subscribers were relatively narrowly distributed around 5 minutes. The trip duration for customers were widely and almost evenly distributed from 9 to 29 minutes.
![TD](/Images/TD.png)
![TD_by_Customer](/Images/TD_by_Customer.png)

The distribution patter for male and female users were similar.
![TD_by_Gender](/Images/TD_by_Gender.png)

The trips happened the most from Thursday 7-8 am and 4-6 pm. There were many trips from 6-9 am on every weekdays. On weekends, there were the most trips around noon.  The distribution patter for male and female users were similar.
![Trips_by_Weekday_for_Each_Hour](/Images/Trips_by_Weekday_for_Each_Hour.png)
![Trips_by_Weekday_for_Each_Hour_Female](/Images/Trips_by_Weekday_for_Each_Hour_Female.png)
![Trips_by_Weekday_for_Each_Hour_Male](/Images/Trips_by_Weekday_for_Each_Hour_Male.png)

The number of trips of customer were higher on weekends, while the number of trips of subscribers were higher during weekdays. Number of trips made by male were higher than that for female on every day. 
![User_Trips_by_Gender_by_Weekday](/Images/User_Trips_by_Gender_by_Weekday.png)


## Summary
The average trip duration for subscribers (long term users) are higher than that for customers (short term / one time user). And subscriber tend to have their trip on weekdays, while customers tend to have their trip on weekends. That indicates that most user for bike sharing services are using for daily commute. They usually don't need to ride for a long time, but need to ride everyday, so they would choose to subscribe the service. People who have longer trip duration might ride the bike for weekend leisure, they don't use the service everyday, therefore they don't subscribe.

To investigate more, I would like to visualize the start location for subscribers and customers on the map to see whether the distribution of start locations are different. I would also like to visualize the number of different user type for different genders.