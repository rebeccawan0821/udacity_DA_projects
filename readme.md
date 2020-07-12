# Ford GoBike System Data Exploration
## by Siqi Wan


## Dataset
Ford GoBike System Data. This dataset is Bay Wheels's trip data for public use. This data is provided according to the Bay Wheels License Agreement. The dataset including bike rental trip information and contains data 2017-2020/03
https://s3.amazonaws.com/baywheels-data/index.html


## Summary of Findings

1. the trip distribution is right skewed
2. The average trip duration: 671.88 and The median trip duration: 558.0
3. Which user type has more trip?
Answer: The subscriber user group has more trips.
4. Does the average trip duration varies between two user type?
Answer: The average trip duration does varies bettwen customer and subscriber group. Customer group has higher average trip duration of 879.4 seconds, which about 250 more seconds than subscriber group.
5. Most trips are taken in March, Sept and Oct.
6. Most trips are taken on Tuesday, Wednesday and Thursday, which make sense since these days are busy working days.
7. Peak hours for trips are 7-9am and 16-19pm, which also make sense about since these are commuting hours.
8. Which station is most popular?
Answer: The Market St at 10th St, San Francisco Caltrian and Berry St at 4th St are three most popular start station among all the stations.
9. The customer group has higher median trip duration value and meanwhile subscriber group has more data in the dataset.
10. There is an increasing trend in the median trip duration from 4-9am. 
11. The median trip duration started to decrease from 15pm.
12. There are two stations(The embarcadero at sansome st and san francisco ferry building), the trip duration median value between customer and subscriber is large. Subscribers starts at these two station has longer trip duration compares to customer group.

## Key Insights for Presentation

1. the trip distribution is right skewed
2. The average trip duration: 671.88 and The median trip duration: 558.0
3. Subscribers and customer trip duration distribution are all right skewed with majority trip duration around 500 seconds.
4. Our dataset has more subscriber data points compares to customer data points.
5. With the trip duration increase, the delta between number of trips for subscriber vs customer is not obvious anymore. This could because:
    a. lack of data(less than 5000 records)
    b. it is also possbile that for users that trips more than 1500 seconds, there is not difference in the number of subscriber trips and customer trips.
6. Most trips are taken in March, Sept and Oct.
7. Most trips are taken on Tuesday, Wednesday and Thursday, which make sense since these days are busy working days.
8. Peak hours for trips are 7-9am and 16-19pm, which also make sense about since these are commuting hours.

