# Ford-GoBike-system-project
Created exploratory and explanatory visualizations for Ford GoBike Data and found that the most common riders are between 25 and 35 years old and they ride for less than 5000 seconds
## by Fidelis Mukudi


## Dataset

The project was about creating visualization for Ford GoBike System Data. The data is available on the url https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv. The data contains details rides but different people of diferent age and sex from different stations to different stations. The data has 183412 rows and 16 columns. The variable of interest was the duration of riding. We analysed how different variables such as age, sex, bike_share_for_all_trip, bike_id, user_type and start_station_id relates to the duration of riding.

To acquire the data, we extracted programmatically using the request library, saved it on a csv file and loaded it to a data frame. We then previewed it visually and programmtically to identify the variables of interest. Next, we checked for the null values, cleaned the data for null values and tested to check that there are no null values. We also removed the zero character at the end of the values in the start_station_id, end_station_id and the year_of_birth then changed the type to integers. Finally, I created the age column by first extracting the years from start time and subtract the years of birth to get the age and assigned it a new column. I then tested visually to see that the age column exists.  


## Summary of Findings

We analysed the Ford bike data using visualizations. The visualizations were univariate, bivariate and also multivariate. 
We bagan with univarate visualizations. We found that most rider rides between 300 and 600 seconds. These were mainly the age group between 25 and 35 years. In addition, we found that about three quarter of the riders are male while the female were almost equal to a quarter of all the riders. We also have the other gender whose percetage was less than 10%.
We also established that there were two types of riders, the subscriber and the customers where the subscribers were composed of about 80% of all the riders. During the riding there are riders that shared the bike and those that did not. We found that those that share the bike were about 80% of the riders. We also establashed that there were 12 common starting stations whith the highest having 3649 riders and the twelfth one having 1761 riders.

Next, we looked at the association of two variable, different variable and the riding duration. We found that across all ages, most riders rode for less than 10000 seconds with the male between 25 and 35 being the majority. This is the most riding age group. On the other hand, the Customers were the user type that rode for longer time than the subscribers. Furthermore, the riders that rode for longer hours are those that did not share the bike. We established that the most common starting stations had very long riding hours compared to the longest hours attained by those in least common stations.

Finally, we also looked at associations having three variables. We found that the more male riders between the age of 20 and 50 rode more than the female and other gender. The highest number of riders across all gender are rode for less than 5000 seconds. We also found that between 50 and 60 years, we have more other gender riding for less than 5000 than the males and females. We also found that within the most riding age group, we have more subscribers than the customers riders.

While considering bike sharing, we found that across all ages, we had fewer riders sharing bikes than those that did not share the bike, however, the majority were between about 21 and 30 years old. Among those that did not sharea bike, we had the majority of riders being above 30 years old while the majority of those that share are below 25 years old.

While looking starter stations, we found that the male riders rode for a shorter period while the other gender has the highest number of durations across almost all starting stations. It was also evident that despite station 58 being one that had the highest number of riders, it had the lowest average riding duration across all the 12 stations. This implied that the majority of the riders from the station must have been riding for shorter periods of time. 

The most interesting feature was that on average, the male rode for a shorter period than the female and the other gender. This is against the expectation because male are expected to ride for longer than female given their masculinity. Another interesting points that the common start has long riding hours but on evarage, it has the shortest riding hours. This implied that short time riders used the station leading to the low average.

In the explanatory visualization, I plan to show visualization for the univariate distribution of age and gender of the riders. Among the bivariate distribution, I plan to show the visualization for the distribution of duration and riding and among the multivariate visualizations, I will show the distribution of age, gender and 12 monst common start stations. 



## Key Insights for Presentation

In the plots for distribution of age among the riders, I increased the size of the bins slightly and provided the units of the axes. For the pice chart, I provided the percentages for each gender and also changed the color codes to appaer to be fading from the gender with the highest percentage to one with the lowest gender.
In the heatplot on Association of age and duration of riding, I labelled the colorbar then provided the units for the axes.
For the fourth visualization, I changed the color styles, to have monochromatic color for all the categories in gender and labelled the horizontal axis.

We found that


* The highest percentage of bike riders are between 25 and 35 years old. 
* Three quarters of the rider are males while the female are almost a quarter while the other gender is 2%.
* The majority of the riders ride for less than 5000 seconds and are aged between 25 and 35 years. The majority of Riders ridding for longer hours are within the same age bracket. A few elders beyond 70 years ride for more than 10000 seconds.
* On average the male ride for a shorter period than the female and the other gender.
* In general, start stations having the highest number of riders do not have highest average riding durations. 
