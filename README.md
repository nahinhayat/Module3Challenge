Module 3 Challenge 


This program uses the prices of Bitcoin on two exchanges, Coinbase and Bitstamp, for a period from January 2018 to April 2018 to find any arbitration spread and possible places to make a profit by buying the cyrptocurrency on one exchange and selling in the other. 

Description:
 
First the data for the exchange's opening, closing, high, and low prices for each day in this time period were imported in from a csv file. This was done for both Coinbase and Bitstamp.


Then the data was prepared for analysis by removing dollar signs, dropping duplicates, and converting all column values to float. 


The two dataframes for each exchange had too much information for our purposes. So a new variable was created for each which only contained the data for the closing prices. 

These prices were then plotted and overlayed on top of each other to get an understanding of which exchange had the lower prices. 


Then three random days were chosen to use in this study. These being: 01/16/2018, 02/24/2018, 03/24/2018. Each day's data was plotted. It was decided after seeing the plots that bitstamp had the lower prices so we found the arbitrage spread for each day and plotted that as well. 

We then found when the arbitrage spread was positive for each day, and then found the spread return. 

Finally, we calculated the potential profit per trade. These results for each were later plotted as well.



Author

Nahin Hayat https://www.linkedin.com/in/nahinhayat/
