# Pyber Analysis 
Analyzing Ridesharing data with Matplotlib and python.
## Purpose 
The purpose of this analysis was to gain insight on Pyber ride sharing data and find conclusions and trends in fare metrics. During this analysis we were able to filter the data through each city type that Pyber operated in and through these city types come to trends involving the average fare and average driver count and take away key summaries that involved this data. From this analysis we then created visualizations of the conclusions we found and therefore were able to understand the data more clearly and therefore help Pyber improve their ride-sharing services. 
## Analysis 
Analyzing the data from the two csv files we were given we were able to create an overview summary of Pyber ride-sharing data for each city type and show the metrics for each city type. 
###
  ![Summary](https://github.com/mckjack/PyBer_Analysis/blob/main/pyber_summary_df.png)
---
#### As we can see there is a huge difference of the amount of rides and drivers between the urban and rural city type. Due to this the average fare price between the two are fairly different with the rural average ride price being $34.62 which is 10 dollars more than the average ride price in an urban area. We also notice that the number of suburban drivers are roughly 6x higher than the amount of rural area drivers and the discrepency between the revenue is huge. From this conclusion we are able to notice that the revenue based upon the total fares of each city type is higher when there is a larger ratio of total drivers to total rides. 
---
#### Further into our analysis we decided to resample the dataframe to show a weekly change in the total fare between the weeks from January to May for each city type. After some resampling in our code we got a new dataframe that resembled the following, 
---
![Resample](https://github.com/mckjack/PyBer_Analysis/blob/main/Average%20Fare.png)
--- 
