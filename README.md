# prophet-challenge
This project aims to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.


Find unusual patterns in hourly Google search traffic (25 points)
Read the search data into a DataFrame. (5 points)

Slice the data to just the month of May 2020. (5 points)

Calculate the total search traffic for the month.(5 points)

Compare the value to the monthly median across all months. (5 points)

Did the Google search traffic increase during the month that MercadoLibre released its financial results? Write your answer in the space provided in the starter file. (5 points)

Mine the search traffic data for seasonality (20 points)
Group the hourly search data to plot the average traffic by the hour of day. (5 points)

Group the hourly search data to plot the average traffic by the day of the week (for example, Monday vs. Friday). (5 points)

Group the hourly search data to plot the average traffic by the week of the year. (5 points)

Are there any time based trends that you can see in the data? Write your answer in the space provided in the starter file. (5 points)

Relate the search traffic to stock price patterns (35 points)
Read in and plot the stock price data. (5 points)

Concatenate the stock price data to the search data in a single DataFrame. (5 points)

Slice the data to just the first half of 2020 (2020-01 to 2020-06 in the DataFrame), and then plot the data. (5 points)

Create a new column in the DataFrame named “Lagged Search Trends” that offsets, or shifts, the search traffic by one hour. (5 points)

Create two additional columns:

“Stock Volatility”, which holds an exponentially weighted four-hour rolling average of the company’s stock volatility. (5 points)

“Hourly Stock Return”, which holds the percent change of the company's stock price on an hourly basis. (5 points)

Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns? Write your answer in the space provided in the starter file. (5 points)

Create a time series model with Prophet (20 points)
Set up the Google search data for a Prophet forecasting model. (5 points)

After estimating the model, plot the forecast. (5 points)

Plot the individual time series components of the model. (5 points)

Answer the following questions in the space provided in the starter file:

What time of day exhibits the greatest popularity? (2 points)

Which day of the week gets the most search traffic? (2 points)

What's the lowest point for search traffic in the calendar year? (1 point)