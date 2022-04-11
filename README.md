# Pyber Analysis 
Analyzing Ridesharing data with Matplotlib and python.
## Purpose 
The purpose of this analysis was to gain insight on Pyber ride sharing data and find conclusions and trends in fare metrics. During this analysis we were able to filter the data through each city type that Pyber operated in and through these city types come to trends involving the average fare and average driver count and take away key summaries that involved this data. From this analysis we then created visualizations of the conclusions we found and therefore were able to understand the data more clearly and therefore help Pyber improve their ride-sharing services. 
## Analysis 
Analyzing the data from the two csv files we were given we were able to create an overview summary of Pyber ride-sharing data for each city type and show the metrics for each city type. 

![Summary](https://github.com/mckjack/PyBer_Analysis/blob/main/pyber_summary_df.png)

As we can see there is a huge difference of the amount of rides and drivers between the urban and rural city type. Due to this the average fare price between the two are fairly different with the rural average ride price being $34.62 which is 10 dollars more than the average ride price in an urban area. We also notice that the number of suburban drivers are roughly 6x higher than the amount of rural area drivers and the discrepency between the revenue is huge. From this conclusion we are able to notice that the revenue based upon the total fares of each city type is higher when there is a larger ratio of total drivers to total rides. 

--- 

Further into our analysis we decided to resample the dataframe to show a weekly change in the total fare between the weeks from January to May for each city type. After some resampling in our code we got a new dataframe that resembled the following, 

![Resample](https://github.com/mckjack/PyBer_Analysis/blob/main/Average%20Fare.png)

We can see that the change between the total fare in each city type differs from week to week, however in the urban city type it stays above a certain threshold each week meaning that the revenue doesn't fall below a certain value. After investigating this further we were able to visualize and make a graph of the following data using the object oriented approach. We got the following, 

![Graph](https://github.com/mckjack/PyBer_Analysis/blob/main/Analysis/Pyber_fare_summary.png)

As we can see in this graph that when urban starts in January of 2019 it does not dip below its starting point whereas rural does drop below its starting point multiple times. This concludes that higher populated dense areas are good for Pyber due to an increase in total revenue and number of drivers and rides. 

--- 

## Summary 
The three recommendations we can make to improve Pyber ride-sharing data are the following,
- increase the number of drivers in rural areas therefore the demand for rides can be met. Some of these drivers are travelling long distances due to the average fare for each driver in rural areas are much higher. Therefore some drivers may miss other trips due to being occupied on a long drive. 
- Decrease the fare for the rides in both rural and suburban areas since the average fares are higher than that of the urban areas. Depending on how the fare is calculated instead of doing it by distance travelled, replace it with time spent travelling therefore decreasing the overall cost for each ride therefore increasing revenue. Likewise increases fares in the urban city types by time spent travelled meaning the average fare would go up. 
- Lastly, decrease the amount of drivers in the urban city types. There is a total of 2,405 drivers and only 1,625 rides indicating that not every driver has done at least one ride. This would increase the average driver fare meaning an increase in revenue. 
 
