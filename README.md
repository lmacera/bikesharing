# Bike Sharing Analysis
Dana and her friend Kate have asked our team to help put together some Tableau visualizations to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.
For this analysis we created a set of visualizations to:
-	Show the length of time that bikes are checked out for all riders and genders
-	Show the Peak hours in the month of August
-	Show the number of bike trips for all riders and genders for each hour of each day of the week
-	Show the breakdown of user types
-	Show the number of bike trips for each type of user and gender for each day of the week
## Resources
-	Data Source: 201908-citibike-tripdata.csv
-	Software: Python 3.6.1, Jupyter Notebook, Tableau
## Results 
Based on the results shown below the bikesharing presentations there are clear trends the bikesharing data for the month of August.

### August Peak Hours
From the below image we can see that the peak hours for ridership are common working commuting hours from 8AM-9AM and 5PM-6PM.
![ Fig 1]( https://github.com/lmacera/bikesharing/blob/main/Resources/Fig%201.PNG )
### Trips by Weekday per Hour
To breakdown the trip peak hours further we prepared a heat mat to show the peak hours based on weekdays. The below heat map shows the peak ridership are common work commuting hours from 8AM-9AM and 5PM-6PM, on the weekdays Monday-Friday , with slowing evening ridership on Wednesday night. Additionally, there is high ridership on Saturday afternoon between the hours of 11AM-5PM.
![ Fig 2]( https://github.com/lmacera/bikesharing/blob/main/Resources/Fig%202.PNG )

### Trips by Gender (Weekday per Hour)
To wrap up our analysis on peak hour ridership we can look further into or Trips by Weekday per Hour analysis and break it down to include peak ridership by gender. From the below heatmap analysis we can see that the peak ridership hours are driven by male ridership.
![ Fig 3]( https://github.com/lmacera/bikesharing/blob/main/Resources/Fig%203.PNG )

### Trips by User Type and Gender
To grasp a better understanding of the ridership by user type and gender we created a dashboard that shows the percentage of user types (Subscribers or Customers) and a heatmap that breaks down peak ridership days by user types and gender. From the below presentation most of the riders are male subscribers that prefer to ride Monday-Saturday with peak days being Thursdays and Friday.
![ Fig 4]( https://github.com/lmacera/bikesharing/blob/main/Resources/Fig%204.PNG )
![ Fig 5]( https://github.com/lmacera/bikesharing/blob/main/Resources/Fig%205.PNG )
### Checkout Analysis by time and gender
Our final analysis provided insight into the length of each rides checkout length and gender. From the below dashboard we can see that no riders checked out a bike for more than an hour and that the majority of the rides had a checkout time of 5-6 minutes. As with our trips and user type analysis we can see that most of the checkouts were males with the peak checkout time at approximately 5 minutes. Though female ridership is significantly lower than the male ridership we can see that the checkout time is approximately 5-6 minutes similar to that of the male rider.
![ Fig 6]( https://github.com/lmacera/bikesharing/blob/main/Resources/Fig%206.PNG )
## Summary
In summary the presented data showed that the majority of ridership is during commuting hours by subscriber user types of which the majority are male. Further analysis with this data set would be to provide a breakdown based on age and user type to see what age group has the most subscribers. Additionally, a bar chart analysis on the top 10 start and end locations would help determine what start and stop locations are most popular, and if any of these stations overlap. If there are certain bikes ant these stations that are utilized more we can then provide a further breakdown on the maintenance required per utilization. 


[link to dashboard]( https://public.tableau.com/app/profile/lisa.macera/viz/BikeChallenge_16403990849060/NYCBikingAnalysis?publish=yes )
