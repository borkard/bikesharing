# Citi Bike Analysis

## Overview of Project
This project focused on analyzing New York City Citi Bike trip history data from August 2019 and producing interactive Tableau visualizations to summarize the data.
Twelve visualizations of the data were created in Tableau Public to analyze the trips histories by gender and time. Seven of the twelve visualizations were included in a Tableau Story as shown in the results. Prior to creating the visualizations, some of the data was cleaned using Jupyter Notebooks and Pandas.

The link to the Tableau Public story is below:
https://public.tableau.com/profile/diana.borkar#!/vizhome/citibike_challenge_16155985817030/CitibikeStory

## Results
The below images are the visualizations from the Tableau Story of the Citi Bike Analysis.

*August Peak Hours:*
![August_Peak_Hours](https://github.com/borkard/bikesharing/blob/main/Images/August_Peak_Hours.PNG)

The above graph is a bar graph that represents the peak hours for Citi Bikes trips. The Number of Trips is displayed on the x-axis and the hour of the start-time is displayed on the y-axis. Based on this visualization, it appears that there are peaks in Citi Bike usage during the commuting hours of 8-9am and 5-6pm. In the early hours of the morning, 2-3am, not many trips are taken.


*Trips by Weekday per Hour:*
![Trips_Weekday_Hour](https://github.com/borkard/bikesharing/blob/main/Images/Trips_Weekday_Hour.PNG)

The visualization above displays the frequency of trips for each day of the week and time of day. According to the visualization, the most trips are taken during 5-7pm on a Thursday, which is also a popular time for most other weekdays. Many trips also occur during Saturday afternoons. There are very few trips before 5am on weekdays. This visualization can be filtered by the Weekday of Stoptime.


*Checkout Times for Users:*
![Checkout_Times_Users](https://github.com/borkard/bikesharing/blob/main/Images/Checkout_Times_Users.PNG)

The visualization above is a line graph showing the Checkout times for users by minutes and hours. The number of bikes checked out is on the y-axis and the hours and minutes are shown on the x-axis. Minute 5 of the trip duration shows a sharp peak in the number of bikes checked out with a sharp decline down to less than 1,000 bikes checkouts out beyond an hour. This visualization can be filtered by the hour of trip duration.


*Gender Breakdown:*
![Gender_Breakdown](https://github.com/borkard/bikesharing/blob/main/Images/Gender_Breakdown.PNG)

The visualization above is a pie chart to break down the gender of the Citi Bike users. A majority of Citi Bike users (65%) are male, with Females representing only 25% of citibike users and Unknown representing 10%.


*Checkout Times by Gender:*
![Checkout_Times_Gender](https://github.com/borkard/bikesharing/blob/main/Images/Checkout_Times_Gender.PNG)

The visualization above is a line graph that shows the Checkout Times by Gender. The number of bikes checkout out is displayed on the y-axis and the hours and minutes of the trip duration are displayed on the x-axis. At the trip duration mark of 5 minutes, there is a sharp increase in the number of bikes checked out by males. The peak trip duration for the majority of bikes checked out by females occurs around 7 minutes. There is a long tail of a limited number of bikes checked out by females for longer than an hour. As shown in the Gender Breakdown, many more males have checked out bikes than females or unknown. This visualization is filterable by gender and hour of trip duration.


*Trips by Gender (Weekday per Hour):*
![Trips_Gender](https://github.com/borkard/bikesharing/blob/main/Images/Trips_Gender.PNG)

The above visualization displayes the Trips by Gender by Weekday per Hour. The heatmap shows when trips occurred throughout each hour of the day (shown on the y-axis) for each day of the week (on the x-axis) split by each gender. Many more trips were taken by males compared to females and unknown and the peak times and days for males were during the work-week around 8am and 5-7pm. Saturday afternoons were also a popular time for males. The peak times for females were around the same times and days, but to a much lesser extent. The trips by unknown gender are pretty much the same throughout the week, with a slight increase on weekend afternoons. The number of trips for the unknown gender are much less than males or females. This visualization is filterable by gender and Weekday of Stoptime.


*User Trips by Gender by Weekday:*
![User_Trips_Gender_Workday](https://github.com/borkard/bikesharing/blob/main/Images/User_Trips_Gender_Workday.PNG)

The above visualization shows the number of trips by type of user (Customer or Subscriber), as well as by the Weekday and Gender. The number of trips for customers are much less than the number of trips for subscribers. Amongst the customers, the gender hardly affects the number of trips and there is only a slight increase in the number of trips during the weekends. Amongst the subscribers, a majority of the trips are taken by males with the most popular day being Thursday. Amongst the subscribers, the unknown gender counts for very few of the trips and the trips by females are much less than those taken by men, but follow the same peaks in the days.


## Summary
Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

Based on the results and visualizations of the Citi Bike trip history data from August 2019, it seems that a majority of the trips are taken by males that are subscribers and most trips occur during commuting hours on weekdays, especially Thursdays. Most Citi Bike trips are under 10 minutes and hardly go past one hour. As the commuting times tend to be the most popular, repairs and maintenance can be done in the early hours of the morning when there are not many bikes in demand.

With the given dataset, I would create two additional visualizations to look at the usertype (customers or subcribers) by age, as well as the number of trips by age and gender to understand who to target.


