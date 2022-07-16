## Bike-Sharing
## July-16-2022

## Overview
The purpose of this analysis is to discern the trip duration, checkout times, and popular starting stations according to weekday and gender. For this analysis, we are using a cleaned version of the 201908-citibike-tripdata.csv dataset where we re-formatted the "trip_duration" column from python's integer datatype to datetime data type.

## Results
The following links provided below will show the tableau view of the worksheet, with a brief summary of the data visualisation noted below:

### Checkout Times for Users
[link to Checkout Times for Users] (https://public.tableau.com/views/Citi_bike_challenge/CheckoutTimesforUsers?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

Description: The length of time that bikes are checked out for all riders. The maximum amount of time that a bike is checked out is 5 minutes.


### Checkout Times by Gender
[link to Checkout Times by Gender] (https://public.tableau.com/views/Citi_bike_challenge/CheckoutTimesbyGender?:language=en-US&:display_count=n&:origin=viz_share_link)

Description: The length of time that bikes are checked out for each gender. The maximum amount of time that a bike is checked out by men is 5 minutes. For women, the maximum amount of time that a bike is checked out by men is 6 minutes. Men outnumber women in using a citi-bike.

### Trips by Weekday per Hour
[link to Trips by Weekday per Hour] (https://public.tableau.com/views/Citi_bike_challenge/TripsbyWeekdayperHour?:language=en-US&:display_count=n&:origin=viz_share_link)

Description: The number of bike trips by weekday for each hour of the day as a heatmap. The most frequent weekdays and times in which a citi-bike is used are Mondays, Tuesdays, and Thursdays from 5:00pm and 6:00pm

### Trips by Gender - (Weekday per Hour)
[link to Trips by Gender - (Weekday per Hour)] (https://public.tableau.com/views/Citi_bike_challenge/TripsbyGender-WeekdayperHour?:language=en-US&:display_count=n&:origin=viz_share_link)

Description: The number of bike trips by gender for each hour of each day of the week as a heatmap. Men and Women both use the citi-bike frequently on Mondays, Tuesdays, and Thursdays from 5:00pm and 6:00pm. However, since men are recorded to use the citi-bike more than women, the heatmaps highlights the difference in each gender's aggregate usage of the bike per weekday and hour.

### User Trips by Gender by Weekday
[link to User Trips by Gender by Weekday] (https://public.tableau.com/views/Citi_bike_challenge/UserTripsbyGenderbyWeekday?:language=en-US&:display_count=n&:origin=viz_share_link)

Description: The number of bike trips broken down by gender for each day of the week by each Usertype. This heatmap further divides the Citi-bike user by usertype and gender in order to see which demographic uses the citi-bike the most per weekday. Subscribers use the citi-bike more than Customers.

### Weekday Usage by Gender and Starting Station ID
[link to Weekday Usage by Gender and Starting Station ID] (https://public.tableau.com/views/Citi_bike_challenge/WeekdayUsagebyGenderandStartingStationID?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

Description: Heatmap breaking down the most frequent weekdays each citi-bike is used depending on each Starting Station ID. The heatmap further differentiates how frequently each gender uses a bike according the Starting station ID and weekday. Broadway & West 122 Street, Christopher Street, and E 16th Street and 5th Avenue are the most frequent starting station used by male bike users on Saturdays.

### Map of Popular Start Stations
[link to Map of Popular Start Stations] (https://public.tableau.com/views/Citi_bike_challenge/MapofpopularStartStations?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

Description: A map depicting each start station. The more frequent the citi-bike was used by the station, the bigger the bubble size. This is within a 1 and 1/2 month date range.


## Summary
The data depicted on each visualisation reveals which users use the citi-bike the most and which users use the citi-bike the least. Marketing teams can either direct their efforts to appeal to their most popular demographic of users on certain weekdays and hours or try to figure out why less women use citi-bike than men. The following dashboard supports this suggestion:

Description: Dashboard on differences in citi-bike usage in a weekday according to gender
[link to dashboard](https://public.tableau.com/views/Citi_bike_challenge/HowCitiBikeusagevariesbyGender?:language=en-US&:display_count=n&:origin=viz_share_link "link to dashboard")

Further analysis on the citi-bike dataset could provide:

    1.) A demographic breakdown of citi-bike users per starting station. Gender and user type are the appropriate filters to look into for the demographic. This can be through a table, histogram, or map.
    2.) A bar-graph of the average age of the user and the trip duration.

