# Ford GoBike Data Exploration

## Dataset

The data consists of information regarding 295,854 Ford GoBike trips from January 2020, 
including duration and other trip characteristics. The dataset has been suggested by Udacity 
and can be found at https://www.lyft.com/bikes/bay-wheels/system-data.


## Summary of Findings

In the exploration, I found that trip duration has a long-tailed distribution, 
with a lot of trips on the low duration end, and few on the high duration end. 
Of the 295,853 records in the dataset, there are 4527 outliers: records above 
3,000 seconds. 
Additionally, the exploration revealed that customers and app users tend to 
take longer rides. Moreover, rides on weekends tend to be longer on average 
compared to weekdays, with more customers than subscribers using the service 
proportionally.
What surprised me the most was that customers, not subscribers tend to take 
longer rides: my initial assumption was that subscribers would ride longer. 
However, this makes sense. Subscribers are more likely to take shorter rides 
for commute, while customers, on the contrary, are more likely to take occassional 
longer rides for leisure. This idea is supported by the observation that more 
customers take rides on weekends, and that the rides on weekends are longer on 
average.
Finally, I looked into trip duration for top five start stations to find that 
specific stations don't have any real effect on average trip duration in the 
context of user type and rental access method: customers and app users take 
longer rides. The interesting observation though is that these most popular 
stations account for proportionally longer trips on weekdays, not weekends. 
Previously we revealed that weekend trips tend to be longer. This might due 
to the fact that popular stations are more often used for work commute during 
the weekdays.  


## Key Insights for Presentation

(1) Though duration variable takes on a large range of values, the typical trip 
duration is between 300-700 seconds (5-12 minutes). This has been reveled by both 
zooming into part of histograms most of the data points lie and by logarithmic 
transformation.

(2) Customers take longer rides than subscribers, with more customers than subscribers 
taking rides on weekends proportionally. This is revealed by 

(3) Specific stations don't shift patterns for user types and rental access method: 
customers and app users take longer rides. However, most popular stations account 
for proportionally longer trips on weekdays, not weekends. This is not the case for 
the majority of data.


