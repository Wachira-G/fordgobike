# Communicate Data Findings, Ford GoBike dataset
## by Gabriel Wachira


## Dataset

In this exploration, we were working with the Ford GoBike dataset. The dataset includes information on individual rides made in a bike-sharing system covering the greater San Francisco Bay area, in February 2019. From [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv). Bike share is an innovative mode of transportation that allows users to make trips using publicly available bikes. It consists of a fleet of specially designed, sturdy and durable bikes locked into a network of docking stations throughout the service area. The bikes can be unlocked from one station and returned to any other station in the system, making bike share ideal for short, one-way trips. As seen [here](https://help.baywheels.com/hc/en-us/articles/360033794232-How-does-bike-share-work-#:~:text=Bike%20share%20is,one%2Dway%20trips). 

The dataset originally had 183,412 entries and 16 variables, and finally 174,067 entries and 20 variables on cleaning. The variables included ‘user_type’, on whether the user was a customer or a subscriber ( “Subscriber” = Member or “Customer” = Casual); ‘member_birth_year’, the year the user was born which generated the ‘age’ variable; ‘member_gender’, the gender which the user identified with; ‘bike_share_for_all_trip’ on whether the user was subscribed to the state or federal assistance programs that target low-income residents; 'duration_mins', on how long a trip took in minutes;  'day', on the day of the week; and 'hour', on the time of day from 00hrs to 23hrs. 


## Summary of Findings

The analysis was aimed at finding out the determinants or what predicted the occurrence or likelihood of a trip. In exploring the data, we observed a highly skewed distribution with most of the trips lasting between 0 and 100 minutes, the majority of the trips (75%) lasted between 1 minute and 13 minutes but there is a long tail from 13 minutes up to 1409 minutes. 

Saturdays and Sundays were the least busy days, likely because, on weekends, fewer people were commuting to work. Thursdays were the most popular, followed by Tuesdays. There was a bimodal peak at 8 am and 5 pm, which coincides with the time most people are commuting in the morning and in the evening. However, the bimodal peaks at 8 am and 5 pm were not observed on weekends. Instead, a gradual rise is observed from 7 am, peaking between 1 pm and 2 pm, then a gradual decline. Trips lasted longer on weekends than on weekdays. This may suggest that people rode on weekends for leisure and on weekdays to commute, or they could just have been in less of a hurry on weekends. The data was for the month of February 2019 hence insights by month and year could not be generated.

A majority of the riders were subscribers (90%) with male users at more than 74%, females at about 23% and other genders at about 2%.  Most of the users were between 25 and 35 years of age. It was unusual finding that several 100-year-olds rode with the service. 10% of the trips were by riders in the ‘bike share for all’ program. 

Males had shorter trip durations than females and other genders. The males however rode for a cumulative 1.26 million minutes, females for 449K minutes and other genders rode for 41K minutes. Female customers had the longest duration of trips, while male subscribers had the shortest duration of trips.


## Key Insights for Presentation

In the presentation, I focus on the time dimension, that is trip duration and when the trips occurred. I will also focus on the riders' characteristics in the context of gender and subscription.