# surfs_up
## Project Overview
We wanted to run an analysis of the local weather on Oahu to persuade and show our investor that the weather was suitable for the proposed Surf and Ice Cream shop, Surf 'n Shake. We were given a SQLite database with weather data, and with this data we analyzed the temperature and precipitation from a number of sites on the island.

## Resources
Data Source: hawaii.sqlite
Software used: Python 3.8.8, Anaconda 4.10.3, Jupyter Notebook, Virtual Studio Code 1.57.0

## Results
### Analysis
The two summaries of the June temperature data and December temperature data are posted in the images below. There were 1,517 temperature observations from December, and 1,700 from June. We can notice a few similarities from comparing the data:
* The mean temperature was slightly warmer in June, almost 75 degrees compared to 71 degrees in December. 
* The maximum observed temperature in each month was very close as well, 85 degrees in June vs 83 degrees in December.
* The Interquartile range between both months was also very close, 4 degrees in the June data and 5 in December.

### Images
<img src = Images/June_Summary.png>
<img src= Images/Dec_Summary.png>

## Summary
We can see from the above analysis that the reputation of Hawaii weather is not unfounded! The difference in the temperature, as seen by the mean from each month, is negligible. The interquartile range along with the standard deviation also show that the temperature is relatively constand throughout the year. There are colder days, as evidenced by the minimum temperature observations, but for the most past the weather was in the 70's or warmer. This shows that the locations is great for both surfing and ice cream, and should encourage potential customers to visit the shop. Some additional information could be gleaned by performing another query like comparing the precipitation between month. We could also plot the temperature vs precipiation to see if there was any correlation between the two.