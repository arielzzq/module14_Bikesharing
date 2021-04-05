# An Analysis on CitiBike Data in NYC in Augest

## Overview of the analysis
The purpose of this analysis is to show the user habit, and operating situation of bike-sharing business in New York City.

## Results
[link to dashboard](https://public.tableau.com/profile/ziqin.zhu#!/vizhome/Challenge_16174206363420/Story1?publish=yes)

![Number_of_Rides](/Images/Number_of_Rides.png)
![Customer_Number](/Images/Customer_Number.png)
![Subscriber_Number](/Images/Subscriber_Number.png)
![TD](/Images/TD.png)
![TD_by_Customer](/Images/TD_by_Customer.png)
![TD_by_Gender](/Images/TD_by_Gender.png)
![Trips by Weekday for Each Hour](/Images/Trips by Weekday for Each Hour.png)
![Trips by Weekday for Each Hour_Female](/Images/Trips by Weekday for Each Hour_Female.png)
![Customer_Number](/Images/Customer_Number.png)
![Customer_Number](/Images/Customer_Number.png)
![Customer_Number](/Images/Customer_Number.png)
 - The number of temperature data collected in was 1700 and 1517 in June and December respectively. 183 more data were collected in June.
 - The mean temperature in June was 74.9 degree and was 71.0 degree in December. The 50% quartile temperatures were 75 degree and 71 degree respectively. 
 - The standard deviation of temperature in June and December were 3.26 and 3.75 respectively.


## Summary
Since the mean and 50% quartile temperatures were both higher in June, the average temperature is higher for June than that for December. A lower standard deviation of temperature in June showed that the distribution of temperature is closer to the mean, so the temperature in June might fluctuate less than December.

Two additional queries to perform to gather more weather data for June and December:
 1. A query that filters the Measurement table to retrieve the Precipitation for the month of June.
	
	session.query(Measurement.date, Measurement.prcp).\
	filter(func.strftime("%m", Measurement.date) == June_str).all()

 2.  A query that filters the Measurement table to retrieve the Precipitation for the month of December.

	session.query(Measurement.date, Measurement.prcp).\
	filter(func.strftime("%m", Measurement.date) == Dec_str).all()
