
# Cyclistic Bike Project 

##Introduction

This is my project for the google data analytics certificate on coursera. The time framework that i will be analyzing would be from september 2025 to august 2026

##Goals 

To answer the next question so the company can take actions in a data based form. 
The question is :

How do annual members and casual riders use cyclistic bikes differently?

##Data

The data its recovered from (https://divvy-tripdata.s3.amazonaws.com/index.html) 
(Note that the data has been made available by Motivate International Inc. under license)
The data was recovered from September 2025 to August 2026.
Note during the analysis the month of March was excluded because in the tables of started_at,ended_at  the format was filled in incorrectly and wrong, without the possibility to use and reformat the information so we can use it, so in this analysis it would be without the month of March.

##Tools
Google Sheets,
SQL
Tableau

##Process
First i join all the data (semptember 2025-august2026) in a single table so i dont have to repeat most of the queries    

ride_id
Unique ID assigned to each ride
rideable_type
Type  of bike available 
started_at
Date and time at the start of the trip 
ended_at
Date and time at the end of the trip 
start_station_name
Name of the station where the trip beginns
end_station_name
Name of the station where the trip ends
start_station_id
ID of the station where the trip beginns 
end_station_id
ID of the station where the trip ends
start_lat
Latitude of starting station
end_lat
Latitude of ending station
start_lng
Longitude of the starting station
end_lng
Longitude of the ending station 
member_casual
Type of membership



##Data Cleaning
The data cleaning process were joining all the data loock for null values and adding column(ride_length_in_mins,day of the week, month)
The query returns 5,039,906 null values in total,  once removed we can start the analysis 


Total rides per month September 2025-August 2026

This graph shows the number of riders in each month


Total number of members are 2,412,835
Total number of casuals are 1,304,771














##Average trip duration per Month
 


























The total average of months in the lapse of Sep 2025 to Aug 2026 by members is 12.10
The total average of monthsin the lapse of Sep 2025 to Aug 2026  by casuals is 18.75 





















##Preference on Bikes


The total number for the preference of the bike :

Casual electric bike  769,775
Casual classic bike   534,996
Member electric bike 1,254,449
Member classic bike 1,158,386 

















##Riders per Day


Something that  can escape at first sight from the graph are the most concurred days for each membership, so we will display them below


Members days with most  riders
Wednesday : 391,550
Tuesday : 391,166
Thursday : 382,107

Casuals days with most riders
Saturday : 272,483
Sunday : 212,167
Friday :205,034










##Average  trip duration per Day 



 





The most concurrent hours for the members are 18:00,17:00 and 19:00
The most concurrent hours for casuals are  alson 18:00,17:00 and 19:00

















The average trip duration on the week by members are 12.38
The average trip duration on the week by casuals are 19.97




















##Hour





Later in the report we discusses the hours where each membership its more active, what we can refer by the line chart at simple sight its we can attribute the peaks and drops to certain activities, like in the morning we can speculate that  the first peak in the members category can be cause by people going to work or school, in the afternoon we also would speculate that people are either returning home or just in their recreational time, that could be an explanation of a peak on both types of memberships 


#Observations

By analyzing the data, some observations came up that are worth mentioning:

The number of users per month (respectively of each group) moves in the same direction with the same ups and downs in the same way

Both casual and  members have a predilection for electric bikes 

Cassuals rise steadily, the peak are also at 6:00 pm, also they initiated with more numbers that the members beginn with

The wednesday its the day where both memberships rides the least


##How do annual members and casuals riders use ciclystic bikes differently?


Casual riders average more trip duration than members

Casuals ride more on weekends mean while members ride more at the beginning and mid week than the end of it 

Casuals have more riders in the after midnight than members 

The riding hours for members has two peaks the first one is at 9:00 am and then drops down and then steadily rises to a final peak at 6:00pm,casual riders instead it's almost just a rise until 6:00 pm after that the numbers starts to drop down

Cassuals tend to have a pretty consistent number of users from monday to thursday, even in numbers there is no that much of a difference until friday 

The average numbe for the casual users in the aftermidnight its bigger than the members one

##Recomendations

Discount
I think that a discount previous to the higher riders season the company should make anadvertisement of a discount on the annual membership for the first year, specially on electric bikes

Promote fitnes and ecology 
Could also make a campaign where to promote healthier lifestyles and a more ecological way to move around the city easier they promote riding bikes

Logistic
To place stations near schools, Malls,parks or a diverse points of interest so people instead of considering taxi or a  ride, they could use a bike 

Carry more weight 
Maybe a reason people dont want to use bikes its because they have to carry some weight, so maybe a good improvevment would be to add a basket so people can carry more weight (it would have to set weight parameters for the weight that the bike can carry considering the weight of the rider)

Community 
One way to asegurate the loyalty of the users its to  create a community around it, this can be done by organizing trips, making races, maybe even a contest where people submit a paintjob to the company and the best one wins a bicycle with that paintjob or other price  






Lighninght 
Because the data also show us that a lot of people also use their bikes after 6:00 pm we could considerate putting a flashlight in the electric  models so people that may struggle to see or that their road isnt well illuminated doesnt feel insecure 

##Conclusion
The analysis shows the difference between members and cassuals, that even where members are the dominant part of the service there is still a lot of room to grow, now we understand some of the practical ways casuals use their bikes and with that in mind Cyclistic can elaborate ways of improving the member tier and making it better 










