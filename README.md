# Bikesharing Analysis for CitiBike

Regina Negrycz 
genglist@yahoo.com 
Module 14 Challenge 
Submitted 31 Jul 2021
NYC_Citibike_Challenge.ipynb 
images/1_Checkout_Times_by_User.PNG
images/2_Checkout_Times_by_Gender.PNG
images/3_Trips_by_Weekday_per_Hour.PNG
images/4_Trips_by_Gender_(Weekday_per_Hour).PNG
images/5_User_Trips_by_Gender_by_Weekday.PNG
images/6_Gender_Breakdown.PNG
images/7_Bike_Repair.PNG
README

# Overview
I analyzed CitiBike bike-sharing data from August 2019 in New York City, New York to assess the possibility of launching a similar bike-sharing program in Des Moines, Iowa. The data includes information about the user, bikes, locations, and trip duration. By understanding the NYC bike-sharing program I can better determine the possibility of starting a similar program in a different metropolitan area.

# Dashboard of Results
[Link to dashboard]
(https://public.tableau.com/app/profile/regina.negrycz/viz/NYC_CitiBike_Challenge_16276051390800/UserTripsbyGenderbyWeekday?publish=yes)

# Deliverable 1 
I converted the trip duration column to a date time data type with a different time format.

# Deliverable 2
I imported the modified CSV file into Tableau and created the following visualizations:
Checkout Times for Users
Checkout Times by Gender
Trips by Weekday for Each Hour
Trips by Gender (Weekday per Hour)
User Trips by Gender by Weekday

# Deliverable 3
I created a story and report of the above 5 visualizations plus two I had created from the module (Gender Breakdown, Bike Repair).

# Results / Analysis

*1_Checkout_Times_by_User
This chart shows the frequency of trip lengths in minutes for all rides in August 2019. Most rides are under 20 minutes in length. A significant portion of trips only last 4-7 minutes in length, implying the service is used for shorter trips meant to bridge the last portion of travel or for those just wanting to try out the service out of curiosity. 
https://github.com/genlgist/Bikesharing/blob/main/images/1_Checkout_Times_by_User.PNG

* 2_Checkout_Times_by_Gender
This chart shows per-trip travel duration data broken out by gender. The curves show minimal variance between the gender of a user. Males used the service at a much higher rate than females or unknown genders. Those without a defined gender had a significantly smaller number of rides, but were longer on average.
https://github.com/genlgist/Bikesharing/blob/main/images/2_Checkout_Times_by_Gender.PNG

* 3_Trips_by_Weekday_per_Hour
This shows a heat map of when users begin their rides broken out by hour of the day and day of the week. Peak usage hours of the bike sharing program occur at commuter hours (7-9 AM, M-F) during the weekdays and the middle of the day on the weekends (10 AM - 5 PM, Sat-Sun). This implies the heaviest use of the service is largely driven by commuters on the weekdays.
https://github.com/genlgist/Bikesharing/blob/main/images/3_Trips_by_Weekday_per_Hour.PNG

* 4_Trips_by_Gender_(Weekday_per_Hour)
This shows a heat map that further breaks down the information in Picture 3 by gender. The chart shows a similar time of usage pattern between genders with the highest usage times being commuter hours (7-9 AM, M-F) during the weekdays and the middle of the day on the weekends (10 AM - 5 PM, Sat-Sun). Undefined users' usage pattern shows more usage on the weekends than weekdays in the 10 AM-5 PM hours.

https://github.com/genlgist/Bikesharing/blob/main/images/4_Trips_by_Gender_(Weekday_per_Hour).PNG

* 5_User_Trips_by_Gender_by_Weekday
This shows a heat map of rides broken out by gender and user type. The service is most used by male subscribers and female subscribers. The chart shows the heaviest usage taking place on Thursday followed by Friday, Tuesday then Monday. The chart also matches our previous results where usage patterns between genders is similar and the unknown users are mostly weekend users.
https://github.com/genlgist/Bikesharing/blob/main/images/5_User_Trips_by_Gender_by_Weekday.PNG

* 6_Gender_Breakdown
This pie chart shows that males make up 65% of the ridership while females make up 25% of the ridership.  Better data would be needed to determine the other 10% currently classified as unknown.  This chart is consistent to prior charts showing males predominantly use the bike sharing service.
https://github.com/genlgist/Bikesharing/blob/main/images/6_Gender_Breakdown.PNG

* 7_Bike_Repair
This heat map shows the number of rides per bikeid which would indicate that the bikes most often used would require more repairs than those less used.  Bikeid 38124 was used 479 times while 34559 was only used once.
https://github.com/genlgist/Bikesharing/blob/main/images/7_Bike_Repair.PNG

#Summary
The bike sharing program in NYC showed success with a large subscriber base. Non-subscribers used the service either for exercise or for tourism on the weekend. To determine if this program would be successful in Des Moines I would need to know if the working demographic is centralized in the downtown area with a large base of commuters. 

#Data Limitations
1. There are hundreds of lines of data with incomprehensible birth years – births beginning in 1885?  It appears as if the system capturing the birth year did not have a check on the birth year since someone born in 1885 is more than likely not using a bike sharing service in 2019, if they were even alive!  An area chart would assist with identifying these anomalies.
2. Analysis should be performed on the starting locations for the bike rides.  Are there locations more popular than others?  If yes, is there a sufficient amount of bikes at that location?  A density map visualization might assist with this analysis.
