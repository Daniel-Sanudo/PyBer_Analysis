# PyBer_Analysis

The aim of this project is to summarize the ride-sharing data for the first quarter of 2019 according to the classification given to the cities as either urban, suburban or rural types. 

This classification is then used quantify the total driver, rides, fares and the average driver and ride fare per city type to identify trends and differences in the service depending on the area.

## Overview of Project

![Pyber_Summary](/Analysis/Pyber_summary_DF.png)

### Urban Cities

The urban cities have the highest ride and driver amount at 1625 and 2405 respectively, as well as the highest fares ($39,854.38). This is the only city type in which there are more drivers than rides. 

The average fare per ride is calculated by dividing the total fare ($39,854.38) by the number of rides. This means that each ride in our urban cities earns us $24.53. 

The average fare per driver is calculated by dividing the total fare ($39,854.38) by the number of drivers which results in earnings of $16.57 per each driver in urban cities.

Urban cities have a higher demand for a pyber ride; however according to our Q1 results, not every driver in urban cities could provide a ride. The ride/driver index for urban cities is 0.675. Whenver this index goes below 1 means that the Fare per Ride will be higher than the Fare per Driver.

### Suburban Cities

The suburban cities have the second highest ride and driver amount at 625 and 490 respectively, as well as the second highest fares ($19,356.33). Suburban cities have a demand for thats 2.6 times lower than urban cities while the fare is 2.05 times less than urban cities.

The average fare per ride is calculated by dividing the total fare ($19,356.33) by the number of rides. This means that each ride in our suburban cities earns us $30.97	

The average fare per driver is calculated by dividing the total fare ($19,356.33) by the number of rides. This means that each driver in our suburban cities earns us $39.50

Suburban cities have a noticeably lower demand for rides; however the fare per ride is higher.

In this case, the ride/driver index is 1.27, this means that each driver in suburban cities drove at least 1 ride during our first quarter, hence why the fare per driver is above the fare per ride.

### Rural Cities

Rural cities have the lowest ride and driver count at 125 and 78 respectively, the total fare in these cities is $4,327.93. Rural cities have 13 times less rides and 30.83 times less drivers than urban cities. 

The average fare per ride is calculated by dividing the total fare ($4,327.93) by the number of rides. This means that each ride in our rural cities earns us $34.62.	

The average fare per driver is calculated by dividing the total fare ($4,327.93) by the number of rides. This means that each driver in our rural cities earns us $55.49.

Rural cities have a really low ride count; the ride/driver index in them is 1.60, meaning that each driver contributed with at least 1.6 rides during our 2019 first quarter.

### Purpose

By analyzing our performance in the different city types in which Pyber provides its service, we can design new business strategies to both improve pyber's earnings, and provide a more affordable price to rural areas. 

The analysis will also consider the earnings on a weekly basis for the first quarter of 2019 to identify highs and lows in the demand and earnings. 

This information is useful to know how the market differs according to the city type. With a clear knowledge of what each city requires, we can implement much more effective strategies that are adjusted to each city type.

## Results

![Fare_Per_City_Type](/Analysis/PyBer_fare_summary.png)

This line chart was made using the weekly fare information for the 2019 Q1 per each city type. The third week of februrary has a noticeable spike in all three city types.

### Urban Cities
Urban cities as mentioned previously have the highest fare value; January has the lowest fares compared to the rest of the months. During the last weeks of february and the first weeks of march there's a noticeable spike which reaches the highest fare value for this quarter. The fare values oscillated between 1600 at a minimum and around 2500 for their maximum.

### Suburban Cities
Suburban cities have a low fare value during march. There's a slight dip during the first week of april which then starts to rise. January shows a stead increase in fares while februrary reaches the highest fare value for suburban cities. The fare values oscillated between 750 at a minimum and almost 1500 for their maximum.

### Rural Cities
Rural cities had a more stable fare value during this quarter; for all this period the fare remained within the 0 to 500 range. Between the 4 analyzed months, january had the lowest fare value. The maximum fare for rural areas happened during the final week of marcha nd the first week of april.

### Business Recommendations

1. Rural areas have a problem with the number of rides that are requested, and the high fare for these. It's possible that the high fare costs cause the citizens of rural areas to avoid using pyber and use an alternative transportation method. We could solve these issues by offering a carpooling campaing or a discounted fare for these sectors which would drive up the ride numbers and, if done properly, increase the total fare. 

2. Researching the route information for the rides at rural areas could help determine the average distance for each ride which influences the gas consumption and the areas with the most movement, this information would make our campaings to provide our service to underserved neighborhoods much more effective

3. Urban areas have a higher driver count than rides taken, which means that we could try boost our service through a advertising campaign to let the people know about our great service and low fares. This way our drivers can each provide at least 1 ride during the quarter.