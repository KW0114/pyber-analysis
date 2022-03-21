# Ride Share Data Analysis

## Overview of Analysis

The purpose of this project was to study the rideshare data to get a better understanding of the
effect that the type of city has on things such as number of rides, number of drivers, and ultimately
the total fare that each type of city accumulates. 

## Results

### Overall Data Summary

![screenshot](https://github.com/KW0114/pyber-analysis/blob/928dae1907188e890e5a2784d64b1323051df84b/Resources/pyber_summary_df.png)

Looking at the chart above, we can see several different relationships between each quantity before
even attempting to visualize this data. Rural areas tend to have more distance between locations of
interest, so it makes sense that the average fare per ride is the highest in this type of city. It also
makes sense that it has the highest average fare per driver, as the lower population would also mean that
there are not as many drivers available. As population numbers rise for suburban and urban areas, we can 
see these numbers go down. 

These insights easily lead to our line chart for weekly fares by city type:

![screenshot](https://github.com/KW0114/pyber-analysis/blob/928dae1907188e890e5a2784d64b1323051df84b/Resources/total%20fare%20by%20city%20type.png)

This data readily agrees with the information above. Urban areas have a much denser population than rural
or suburban areas, which means that much more people are looking for rides. We can also take into 
account that many people who live in urban areas do not own a car due to the concentrated population. 
This will result in MUCH more people calling for a ride sharing service. Although the urban areas
boast the highest amount of rides (and revenue), the average cost per ride is actually the lowest in these
areas, most likely because customers need to travel much shorter distances than those who live in the other
city types. This alone will cause each ride to cost less. Due to this, the average fare per driver is
also the lowest!

## Summary

 Business recommendations based on the data:

1. If the goal is to close the gap for average fares per ride among the city types, maybe the business could
adopt some type of a "short ride" fee. If rides are under a certain mileage, an extra fee will be applied. 
This could also help out drivers as their average fare per ride would increase, and they will be more
fairly compensated for their time accepting such a short ride. 

2. It seems as though there is a much larger jump down in the average fare per driver from suburban to urban 
cities than there is in the average fare per ride. This is most likely because too many drivers sign up, 
and so they are taking a lot of the revenue away from any other driver who is already in the system.
Possibly the company could enact a driver limit that is proportional to either the population of the area, or
maybe even the popularity of the app in that certain area. The second option could help to avoid running out
of drivers in touristic areas, where the documented population doesn't match the actual amount of people in
the city at an given point in time. 

3. The company could try to offer an incentive (such as a small discount, or a boost in rewards "points") for calling
rides during typically slow times in the year. Even with the small money lost on the discount, if the frequency
of rides increases, then it could become a gain overall for these numbers. 