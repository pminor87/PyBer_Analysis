# PyBer_Analysis

## Overview of the Analysis:
- The purpose of this analysis is to show the relationship of fares as it relates to average by ride, driver and city type.
- The fist step was to use the groupby() function to find the count of riders, sum of drivers, and sum of the fares to be able to calculate the average fare by rides and drivers.
- Next we formatted the data and put it into a new dataframe:

<img width="600" src="Resources/Pyber Summary DataFrame.PNG" align="center">


<br>

## Results:
### Ride-Sharing Data among City Types:

- Urban
    - Highest amount of Rides, Drivers and Fares.
    - Lowest Average Fare per Ride and Driver.

<br>

- Suburban
    - Second highest amount of Rides, Drivers and Fares.
    - Second lowest Average Fare per Ride and Driver.

<br>

- Rural
    - Lowest amount of Rides, Drivers and Fares.
    - Highest Average Fare per Ride and Driver.

<br>



<br>

<table>
  <tr>
    <td><img src="analysis/PyBer_fare_per_city_type_summary.png" width= height=></td>
  </tr>
 </table>

<br>

## Summary:

#### The data indicates that the lower the density population for each city the lower the amount of rides and drivers there are and vice versa. However, the density of the city also seems to dictate the average fare per ride and driver.

### Reccomendations to Maximize Profit:
- Charge more per mile for denser populations since the trips are more likely shorter but the efficiency of the trips would be lower based off assumed traffic.
- Set a mandatory minimum tip for rural areas to incentive drivers to continue their business in this area since they may be waiting on rides due to the lower amount of total rides for this area.
- Assign drivers to higher populated cities based off the fuel efficiency of their vehicle in order to save gas expenses.