# PyBer Analysis Challenge 
## Project Overview

1. Create a ride-sharing summary DataFrame for each city type
2. Create a multi-line chart of total fares per city type

In addition to Original Module tasks:
1. Determine the mean, median, and mode for the total number of rides for each city type, the average fairs for each city type, and the total number of drivers for each city type.
2. Create box-and-whisker plots to visualize the number of rides for each city type, the fares for each city type, and the number of drivers for each city type. 
3. Create a pie chart to viualize the percent of total fares, the percnt of total rides, and the percent of total drivers.

## Purpose of Analysis

Explore data for PyBer using Python, Pandas, and Matploblib from a set timeframe to improve access to the ride-sharing services and well as determine affordability for underserved neighborhoods. Determine the data sets for Urban, Rural, and Suburban city types, and see how these three city types differ. By creating a ride-sharing summary DataFrame for each city type, it can be explored how the fares are affected for each city type. This data can then be used to determine unique business models for each data type, and determine what methods PyBer should explore to aid its drivers in each city type.

## Resources
* Data source: 
* Software: Python 3.7.6, Anaconda, Conda, Jupyter-Notebook, Pandas, Numpy, Matplotlib, GitBash 

## Overview of Analysis 
This in-depth analysis, created after doing an exploration of the city types in terms of mean, median, and mode in fares, driver counts, and ride counts, can be used to determine future course of action for PyBer. Which city types are seeing the most riders, how many riders are there in the different city types, and how many drivers are there per riders can all be used to figure out where the best business is happening for PyBer. Is it worth investing time and energy into all three city types? Are any of the markets oversaturated? With this data, PyBer can look to the future and figure out how to expand its business.

## Results 
### DataFrame Summary of City Types
![PyBer_Summary_df](https://user-images.githubusercontent.com/88064181/131526268-dcf2e422-a9f9-4f4b-8deb-5d12b31566ab.png)

As seen above by the summary DataFrame for Rural, Suburban, and Urban cities, one can see how the oversaturation of drivers in a market can affect average fare per ride. There are more urban drivers than rides which has lowered the average fare per ride and per drivers. On the opposite end of the spectrum is the rural cities which have more rides than drivers. This has raised the average fare per ride and per drivers. The suburban city also has more rides than drivers, but the ride fare and average fare per driver has not be affected as much as the lack of drivers affected the rural city fares. 

### Total Fare by City Type
![PyBer_fare_summary](https://user-images.githubusercontent.com/88064181/131526311-b5b8e6fc-3192-4e0e-833b-0885b7ff05f0.png)


While the rural city drivers are getting more money on average per ride, the rural city overall is making much less money in fares than the suburban or urban cities. As is expected, the urban city is bringing in the most amount of money for PyBer, followed by the suburban city, and finally the rural city. All three of these cities followed similar fare increase spikes at the end of February. The Urban city then sees many dips and spikes through March before taking a steep dive in the beginning of April back to a steep increase in April. The Suburban city sees a rapid decrease in fare at the beginning of March before evening out, dipping down in the beginning of April, and then finally seeing another spike in fare at the end of April. The Rural city fare seems to stay the most steady with peaks at the end of February and then staying steady after a few peaks in March.  

## Recommendations
* The rural city fare may be so much higher than urban city fares because the rural city is so much more spread out than the urban city. This means the driver's in the rural city will be driving longer distances to bring a ride to their location, and may not have a paid ride back to where they originated from. Even though rural driver's are being paid more, are they actually making more money, or is this higher fare just covering the cost of gas and the time used to accommadate the mileage driven? More research should be done into the specific rides being taken in the rural city to maximize the money made for time spent by drivers driving rides. Driver's lose out on money if they have to drive out to a far away end point and then drive back ot a less rural area to be able to pick up a new rider.
 
* The urban city has more drivers than it does rides. This oversaturation of drivers means that the drivers have to be competetive with each other to get rides. If the company does not do something to promote more rides, eventually drivers will leave the company because they are not able to make a living wage. If too many drivers leave the company, the rides needed to be taken may soon overcome the number of drivers. If it is not possible to have a promotion to encourage riders to get PyBer rides in the urban city, it may be necessary to give the drivers a ranking scale to limit the number of drivers qualified to drive in the urban city.  

* A more in depth analysis should be used to investigate the circumstances surrounding the spike of rides in February amongst all city types. Was this the results of a promotion for cheaper rides, a weather phenomenon, aInvestigate why rides spike in February amongst all city types. Once the incentive for getting rides with Pyber has be identified, it needs to be exploited. If it is weather-related, how can PyBer capitalize on inclement weather during all months of the year. If it was some sort of event, how can PyBer sponsor other events to become the main ride company for those events? If it was just a fluke that all three cities spiked at once, PyBer then needs to look at where rides dip for each city and run a special to promote more rides during those low days of rides. 

* A more thorough look at the data should be investigated for the beginningof April for the Urban data. Such a steep decrease followed by a rapid increase is an anomaly. The data may be skewed, or a data point may not have been inputted correctly. If this is not a technical flaw, why did the fare decrease so dramatically and then increase for the urban data? 
