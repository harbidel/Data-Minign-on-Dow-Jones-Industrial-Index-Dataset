# Data-Minign-on-Dow-Jones-Industrial-Index-Dataset
DBSCAN and K-means Clustering Algorithm on Dow Jones Industrial Index Dataset. It has been used in computational investing research.

## Additional Information

In predicting stock prices you collect data over some period of time - day, week, month, etc. But you cannot take advantage of data from a time period until the next increment of the time period. For example, assume you collect data daily.  When Monday is over you have all of the data for that day.  However you can invest on Monday, because you don't get the data until the end of the day.  You can use the data from Monday to invest on Tuesday.  

In our research each record (row) is data for a week.  Each record also has the percentage of return that stock has in the following week (percent_change_next_weeks_price). Ideally, you want to determine which stock will produce the greatest rate of return in the following week.  This can help you train and test your algorithm.

Some of these attributes might not be use used in your research.  They were originally added to our database to perform calculations.  (Brown, Pelosi & Dirska, 2013) used percent_change_price, percent_change_volume_over_last_wk, days_to_next_dividend, and percent_return_next_dividend.  We left the other attributes in the dataset	in case you wanted to use any of them. Of course what you want to maximize is percent_change_next_weeks_price.

Training data vs Test data:
In (Brown, Pelosi & Dirska, 2013) we used quarter 1 (Jan-Mar) data for training and quarter 2 (Apr-Jun) data for testing.
