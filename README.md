
# Ford GoBike System Data
## by Darine Battikh


## Dataset

> Ford GoBike is a bike sharing system located and covering the San FranciscoBay area. It provides more than 4,000 bikes distributed across different accessible locations allowing customers to get bikes from one station and return to any other station in the system, making them ideal, accessible, and convenient for one-way trips, for special and urgent trips. The bikes are available for use 24 hours/day, all days of the week, and all days of the year. Customers can simply purchase one ride for a detemined number of hours or can become subscribers through a monthly or yearly subscriptions.

> The dataset includes 183,412 bike rides with 16 features describing:

>> Characteristics of the a trip: Duration in seconds, user type, memebers birth year, members gener, bike share for all trip.

>> Start time and place:  Start station id, Start station name, Start station latitude, Start station longitude.

>> End time and place: End time, , End station id, End station name, End_station latitude, End station longitude.

>The variables in data sets are mostly categorical with the exception for the ride duration, the member birth year, the start and end stations, and longtiude and latitude.

## Summary of Findings

> There are 329 different stations in the system. When displyaed the top 10 start stations, there was no significant difference between the start stations. They seem all convienint and close to the memebers and members do not show specific preference to any. The same applies to the end stations.

> There are 4618 bikes in the system. When sorted by most used bikes, there was no difference among all bikes as the counts of all of them were close. For that, we can say that neither customers nor subscribers have a specific preference for neither of bikes.

> 89% of members are subscribers and only 11% are customers. This shows that most of the users are members committed over monthly or yearly subscriptions.

> More than 75% of members are males, in contrast to only 23% female and 2% identified as others.

> When it comes to the members' ages, more than 10,000 members are born in 1988 meaning they are aged 34 years old (by the year 2022). The members age distibution showed a peak between 30 and 35 years old.

> The duration in seconds were not a clear indication of the rides' durations. For that, the data was transformed to minutes which finally stated a peak in 10 minutes for a bike duration and that the majority of rides last between 3 minutes to 30 minutes knowing more than half of rides last less than 10 minutes.

> As the data is extracted for the month February 2018 only, we were not able to check the distrubtion of rides among the months. For that, the analysis focused on the days of the week were we found that Thursday and Tuesday are the days having most rides with 35,000 and 31,000 rides respectively. This was applied to the end days and had the same observation with Thursday and Tuesday having most rides. We can conclude here that the majority of rides starts and ends on the same day and that these two days have special movements and traffic.

> When we studied the relation between the days of the week and the trip duration, we found out that the longest rides are taken on weekends whereas we previously concluded that most of rides are taken on Tuesday and Thursday. This can be explained by the fact that most people use bikes for required trips on weekdays and lesser people use them on weekends for enjoyable trips and leisure.

> A boxplot studying the relationship between user type, ride duration, and days showed that subscribers have a consistent usage of bikes all over the week whereas customers longer rides especially on the weekends.

> A scatter plot showed that Female members have more and longer bike rides than males and those identified as other.

> A final barplot has demonstrated intersting and surprising insights: female in 50 - 60 age groups have longer rides than other younger females and all males. The longest ride belongs to people identified as other aged between 30 and 40 followed by those aged above 50 years old, in the same gender type.

## Key Insights for Presentation

> There is no significant difference in the start nor in the end locations. They seemed all accessible by all members. There was no difference in the usage of specific bikes reflecting that members are indifferent regarding the available bikes (no preference).

> Subscribers are almost 8 times more than customers, yet, customers tend to have longer bike rides especially on the weekends. Subscribers have a consistent usage of bikes all over the week. For the weekdays, there was a slight differnce in days with Thursday and Tuesday having the most rides.The longest rides are on weekends, and all trips don't exceed 200 minutes per day. Generally, all rides start and ends on the same day.

> Males consist of 75% of the members compared to 23% females and only 2% ientified as other. Yet, female have more and longer trips compared to other gender types.

> People with most trip are aged between 30 and 35 years old, which can be explained by the fact that this age group is the most present in the dataframe with a peak for the 34 years old.  

> On average, most trips last 10 minutes and more than a half of trips are less than 30 minutes. Generally, longer bike rides have place in the weekends, yet, more bike rides have place on weekdays. 

> When it comes to gender and age groups, people above 40, in almost all gender types, have longer trip duration than younger people, considering that we considered people above 20 years old in this analysis. Interestingly, female in 50 - 60 age groups have longer rides than other younger females and all males. The longest ride belongs to people identified as other aged between 30 and 40 followed by those aged above 50 years old, in the same gender type.