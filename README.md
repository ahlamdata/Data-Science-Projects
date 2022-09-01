# Exploration of the CoGo Bike Sharing Sytem Data
## by Ahlam Mustapha


## Dataset
>This dataset contains a total of 16,868 bicycle rides from CoGo for the entire year of 2019 with 11 features namely trip_id, start_time, end_time, tripduration, from_station_name, to_station_name, usertype, gender, birthyear, start_date, and end_date. 
This data can be found on the CoGo [website](https://cogo-sys-data.s3.amazonaws.com/index.html) and the feature descriptions can be found [here](https://cogobikeshare.com/system-data). 

>Although the suggested data on this was about the FordGo Bike, I wanted to get data for an entire year hence I decided to use the CoGo bike sharing data from the Columbus Area. I downloaded the entire dataset for the year 2019 which was collected on monthly basis. Then I proceeded to clean this data and then merged them into one master data for exploration. 


## Summary of Findings

> The main finding from my exploration is that tripduration which is my variable of interest did not have any clear relationship with any of the other features particularly during the bivariate analysis. However, when I introduced a third variable like the usertype into the plot showing the relationship between tripduration and age, it was quite clear that all customers who were not subscribers had very low trip durations compared to those who were subscribers. The ages of these customers were also between 20 and 60 years old.

>Moreover, some interesting insights were discovered from the other variables. It could be seen from the analysis that, majority of CoGo bicycle riders were males and they were subscribers. The median age of riders was around age 40 and above. Another surprising insight was the fact that the day with the most rides was Wednesday among all the other days of the week. The month with the most rides was May which happens to be in the spring season. 


## Key Insights for Presentation

> Most of the trip duration fell between 100 and 1000 seconds. 
Front St & Town St was the most favoured start station with a total frequency of 7.7%.
Birth year had no influence on how long a trip took
Customers who were not subscribers did not take long trips
The majority of the 'subscribers' seem to be in their 40's
