# CitiBike Analysis & Visualization

## Description:

The task we have is to accomplish the following:
Complete two technical analysis tasks, create visualizations to help understand the ride data and create a tableau story to present the results. The elements of this are to execute:

1) Change Trip Duration to a Datetime Format.
2) Create Visualizations for the Trip Analysis
3) Create a Story and Report for the Final Presentation


## Data transformation with Python
#### Technical analysis task # 1

Data Transformation with Pandas

![Citibike_dataframe](https://user-images.githubusercontent.com/91839403/155864195-17877044-4596-4a39-af25-f6a8ab949f59.jpg)

Initial Data Types: 

![Citibike_datatypes_initial](https://user-images.githubusercontent.com/91839403/155864196-63d00ffe-48bb-4ae0-8c79-e21b200fceb6.jpg)

Tripduration to.datetime 

![Citibike_tripduration_to_datetime](https://user-images.githubusercontent.com/91839403/155864206-0a298170-7fdf-4e83-b604-4be040e6eade.jpg)

Post Transformation Datatypes and .csv file save.

![Citibike_datatypes_2_filesave](https://user-images.githubusercontent.com/91839403/155864217-aec6bb8e-1638-4d7b-9352-1424fb4c7867.jpg)

## Data Analysis with Tableau
#### Technical analysis task # 2

Checkout Times for Users Viz:

![Checkout times for all users](https://user-images.githubusercontent.com/91839403/155864310-aac425b8-b153-4ff7-a9e0-272f972150b4.jpg)

Checkout Times for Users by gender Viz:

![Checkout times by gender](https://user-images.githubusercontent.com/91839403/155864326-01741af4-ce19-48a1-ba5a-6f7fb9fc3400.jpg)

Heatmap of trips by hour

![Heatmap of trips by hour](https://user-images.githubusercontent.com/91839403/155864367-57eaf7cb-d70f-4d1d-ae1d-a087f784dcb5.jpg)

Heatmap of trips by hour and gender

![Heatmap of trips by hour and gender](https://user-images.githubusercontent.com/91839403/155864402-2becae87-a866-4b63-a2dc-025f342d24b0.jpg)

Heat map of User Trips by Gender by Weekday

![user trips by hour gender and user](https://user-images.githubusercontent.com/91839403/155864496-a2d14ff1-97fd-483a-982c-9fbd49d71f89.jpg)

## Summary

### Purpose

This analysis is being conducted on NYC Citibike data to review usage, understand the usage, demographics and business drivers to understand opportunity in other cities and guide decisions in structuring the business for portability.

### Analysis
#### Geographic, demographic and user data

![image](https://user-images.githubusercontent.com/91839403/155865583-41ee6062-275f-427d-abb6-e04d5e795e3e.png)

This analysis shows the highest usage by location in NYC.  It is clear tht the highest usage is in the most populated, busiest part of the city.  This could be due to work or tourism in the area.  More analysis will be conducted to draw conclusions on that hypothesis.  Interesting to learn in this is that subscriptions drive the most usage.  This suggests that the users plan to use the bikes regularly, benefit from the subscription and drive more usage that random users.  This would suggest that work and not tourism is the driving force behind the ride usage.  When looking at demographics for gender men dominate the subscribers who use the bikes.  This does begin to shape a customer type and more analysis would be helpful but it seems from this first pass that citiBike connects with men in high population density areas.

#### Trip length

![image](https://user-images.githubusercontent.com/91839403/155865711-17683890-3abc-436a-9dd9-0ea5d18447ec.png)


The trip length data shows that the bulk of trips are less than 30 minutes and the most frequent duration is 6 minutes.  This is true for both men and women based on the gender analysis included.  The significant spike at the 6 minute mark is interesting.  One analysis not performed here but could be very useful would be comparing high frequency start points with subway of public transport locations.  The time and start and stop locations could align with public transportation locations and citiBikes provide a useful bridge from train to workplace.  IF so that would provide a useful insight into the portability of the business model.

#### User age demographics

![age and gender of users](https://user-images.githubusercontent.com/91839403/155865980-22cc824b-12cf-4a17-94a5-07e1deaaac1c.jpg)

We conducted a quick analysis of users and subscribers by gender and age.  Males born between 1980 and 2000 create the highest population of subscribers.  The ages of the women align to this as well.  This does contiue to support the hypothesis that these are working professionals using the service.


#### Peak hour demand

![Peak hours with users and gender analysis](https://user-images.githubusercontent.com/91839403/155866031-307f7de6-b326-43fb-ab77-2e1e86801787.jpg)

We also conducted and analysis of peak use by hours and included a breakdown of those hours as it relates to users and gender.  There are two peaks during the da.  the first is between 7am and 9am and the second is between 4pm and 7pm.  Males are the higest users but the female use pattern matches that of the males. Subscription vs. random user also dominates use during those times.


#### Gender and user type

![Trips by gender and user type](https://user-images.githubusercontent.com/91839403/155866079-78a78a89-5908-477a-aff7-6dc7e33cc4dd.jpg)

We analyzed other use data by hour for gender and users and are able to conclude the same thing.  Males and subscribers are the most frequent users during the morning and evening commute.  This analysis also showed that mondy-friday are the highest usage days validating the relationship from work to citiBike users.

#### Utilization and Maintenance

![bile utilization and maintenance](https://user-images.githubusercontent.com/91839403/155866122-30177581-50f8-4a9a-8f91-caf1ad945219.jpg)

Finally we analyzed the bike usage and maintenance demand to understand the investment required to start and support the business.  This shows that many bikes see little to no use.  Removing them from the mix revelas that in the right location with the right volume of bikes the consumption can be supported with teh bikes in the system.  There needs to be additional analysis to understand the balance between capacity and demand.  Enough bikes must exist to support the subscribers. 

## Conclusion

The analysis shows that male subscribers are driving the use of citiBikes in NYC during business hours.  There are many bikes that see little to no use and that could be an opportunity to lower start up costs and focus on males between 20-40 years old.  Most custoomer and subscriber analysis would help define our initial target customer.  The connection of citiBike hub locations to public transportaion would be a recommended analysis.  The usage shows peak demand on weekdays at two times, the morning and evening commute.  There may be growth opportunites in areas of recreational use and with women.  To launch we clearly can define what the use characteristics are of the NYC customers and could model in other cities.











