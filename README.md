Module 3 Challenge 


This program uses the prices of Bitcoin on two exchanges, Coinbase and Bitstamp, for a period from January 2018 to April 2018 to find any arbitration spread and possible places to make a profit by buying the cyrptocurrency on one exchange and selling in the other. 

Description:
 
First the data for the exchange's opening, closing, high, and low prices for each day in this time period were imported in from a csv file. This was done for both Coinbase and Bitstamp.

![pic]https://github.com/nahinhayat/Module3Challenge/blob/main/screenshots%20for%20Module3Challenge%20README/Screen%20Shot%202023-03-08%20at%2010.39.24%20PM.png


Then the data was prepared for analysis by removing dollar signs, dropping duplicates, and converting all column values to float. 

![pic]https://github.com/nahinhayat/Module3Challenge/blob/main/screenshots%20for%20Module3Challenge%20README/Screen%20Shot%202023-03-08%20at%2010.41.50%20PM.png

The two dataframes for each exchange had too much information for our purposes. So a new variable was created for each which only contained the data for the closing prices. 

![pic]https://github.com/nahinhayat/Module3Challenge/blob/main/screenshots%20for%20Module3Challenge%20README/Screen%20Shot%202023-03-08%20at%2010.44.52%20PM.png

These prices were then plotted and overlayed on top of each other to get an understanding of which exchange had the lower prices. 

![pic]https://github.com/nahinhayat/Module3Challenge/blob/main/screenshots%20for%20Module3Challenge%20README/Screen%20Shot%202023-03-08%20at%2010.46.38%20PM.png

Then three random days were chosen to use in this study. These being: 01/16/2018, 02/24/2018, 03/24/2018. Each day's data was plotted. It was decided after seeing the plots that bitstamp had the lower prices so we found the arbitrage spread for each day and plotted that as well. 

![pic]https://github.com/nahinhayat/Module3Challenge/blob/main/screenshots%20for%20Module3Challenge%20README/Screen%20Shot%202023-03-08%20at%2010.48.51%20PM.png

![pic]https://github.com/nahinhayat/Module3Challenge/blob/main/screenshots%20for%20Module3Challenge%20README/Screen%20Shot%202023-03-08%20at%2010.50.16%20PM.png

We then found when the arbitrage spread was positive for each day, and then found the spread return. 

![pic]https://github.com/nahinhayat/Module3Challenge/blob/main/screenshots%20for%20Module3Challenge%20README/Screen%20Shot%202023-03-08%20at%2010.53.00%20PM.png

Finally, we calculated the potential profit per trade. These results for each were later plotted as well.

![pic]https://github.com/nahinhayat/Module3Challenge/blob/main/screenshots%20for%20Module3Challenge%20README/Screen%20Shot%202023-03-08%20at%2010.54.18%20PM.png

Author

Nahin Hayat https://www.linkedin.com/in/nahinhayat/
