# prophet-challenge
This project aims to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.


Find unusual patterns in hourly Google search traffic 
Read the search data into a DataFrame. 

Slice the data to just the month of May 2020. 

Calculate the total search traffic for the month.

Compare the value to the monthly median across all months. 

Did the Google search traffic increase during the month that MercadoLibre released its financial results? Write your answer in the space provided in the starter file. 

Mine the search traffic data for seasonality 
Group the hourly search data to plot the average traffic by the hour of day. 

Group the hourly search data to plot the average traffic by the day of the week (for example, Monday vs. Friday). 

Group the hourly search data to plot the average traffic by the week of the year. 

Are there any time based trends that you can see in the data? Write your answer in the space provided in the starter file. 

Relate the search traffic to stock price patterns 
Read in and plot the stock price data. 

Concatenate the stock price data to the search data in a single DataFrame. 

Slice the data to just the first half of 2020 (2020-01 to 2020-06 in the DataFrame), and then plot the data. 

Create a new column in the DataFrame named “Lagged Search Trends” that offsets, or shifts, the search traffic by one hour. 

Create two additional columns:

“Stock Volatility”, which holds an exponentially weighted four-hour rolling average of the company’s stock volatility. 

“Hourly Stock Return”, which holds the percent change of the company's stock price on an hourly basis. 

Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns? Write your answer in the space provided in the starter file. 

Create a time series model with Prophet 
Set up the Google search data for a Prophet forecasting model. 

After estimating the model, plot the forecast. 

Plot the individual time series components of the model. 
