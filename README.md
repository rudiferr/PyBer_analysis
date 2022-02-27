# "PyBer_analysis" Week 5 Challenge
## Overview of the PyBer Ride Sharing Analysis
<!--- Explain the purpose of this analysis. --->
After performing the initial analysis and creating a bubble chart of the PyBer ride sharing data, we saw that average fares of under-serviced cities were drastically higher compared to those that have a high presence of available drivers.

![Image of bubble chart comparing average fares, number of rides, and driver availability](https://github.com/rudiferr/PyBer_analysis/blob/main/analysis/Ride-Sharing_Data.png)

We were tasked with creating a new dataframe to analyze the weekly shifts in the average fare of each city to get a better understanding of what changes need to be made.

## Results
<!--- Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types. --->
![Dataframe of ride share statistics based upon city](https://github.com/rudiferr/PyBer_analysis/blob/main/analysis/PyBer_dataframe_summary.png)
The dataframe above shows that there is an inverse relationship with the Average Fare per Ridee ecompared to every other metric; this results in a disparity for the consumer that in turn is not profitable for PyBer.

![Image of line chart comparing weekly average fares of each city](https://github.com/rudiferr/PyBer_analysis/blob/main/analysis/PyBer_fare_summary.png)
The linechart above shows that total ride fares fluctuate greatly in the Spring season, with peak profit happening during February and potential revenue being incredibly inconsistent throughout the month of March. Things become more interesting at the end of April, where urban environments are producing the same highs from February, suburban areas are also trending upwards, but rural communities are outputting low numbers and continuing to trend downwards.

## Summary
<!--- Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types. --->
As obtained from the bubble chart made earlier, we can conclude that ride counts and driver availability are directly proportional to each other, while average fares are inversely propotional to the prior mentioned. Obtaining access to more data such as geographical start and ends of the rides and distance of the rides will allow us to better understand the habits of the customer base of a certain city and can better answer which of the three qualities should be addressed first.

Along the same vein of researching, additional measures should be put into finding a solution to the drop in total fares for rural and urban areas. The Drop during the end of April trends downward in a rather alarming spike, and could be a result of the irratic fare prices during the month before it.

Though, if one thing is certain is that driver availability might be a huge limiting factor. Ride counts hit a theoretical maximum due to driver availability, and so logically it makes sense to think that driver availability will bottleneck revenue generation before anything else.
