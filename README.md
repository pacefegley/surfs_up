# surfs_up
SQLite, SQLAlchemy

### Overview of the analysis
The purpose of this analysis is to further dive into whether temperatures in Oahu will stay warm enough year round to sustain a surf and ice cream shop.

### Results
- The temperatures in June are very warm, with the mean temperature just below 75 degrees.
- The temperatures in December are cooler than in June, but still not cold by any means. The mean temperature is 71 degrees, just about 4 degrees cooler than the mean temperature in June.
- The minimum temperature in December is 56 degrees, which will be too cool for ice cream, but in reviewing the summary statistics, that looks to be an outlier (see below)

![image](https://github.com/pacefegley/surfs_up/assets/119641907/fe70eb1d-981e-4ac9-aa4f-d0ded96decc7)
![image](https://github.com/pacefegley/surfs_up/assets/119641907/6da96acd-2a45-4150-ad2b-1b50c3c5e532)


### Summary
From the statistical analysis, I would conclude that the weather is warm enough in Oahu to support an ice cream and surf shop year round. If I were going to dive into it more deeply, I would look at a couple of more options:
- query the entire yearly dataset and group the mean temperatures by month to identify if there is a cold month between December and June that we could have missed with this analysis.
- I would also look at the standard deviation from across the yearly dataset to see how close we stay to the mean year round.