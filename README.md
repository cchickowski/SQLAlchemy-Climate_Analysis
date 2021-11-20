# SQLAlchemy-Climate_Analysis

## Climate Analysis and Exploration
To begin, use Python and SQLAlchemy to do basic climate analysis and data exploration of your climate database. All of the following analysis should be completed using SQLAlchemy ORM queries, Pandas, and Matplotlib.

Start by finding the most recent date in the data set.

Using this date, retrieve the last 12 months of precipitation data by querying the 12 preceding months of data. Note you do not pass in the date as a variable to your query.

Select only the date and prcp values.

Load the query results into a Pandas DataFrame and set the index to the date column.

Sort the DataFrame values by date.

Plot the results using the DataFrame plot method. Output:

(https://github.com/cchickowski/SQLAlchemy-Climate_Analysis/blob/b4c649aaf447b3c43b2fb3448dcb1965cf62ae57/Precipitation_Analysis.png)

## Station Analysis

Design a query to calculate the total number of stations in the dataset.

Design a query to find the most active stations (i.e. which stations have the most rows?).

List the stations and observation counts in descending order.

Which station id has the highest number of observations?

Using the most active station id, calculate the lowest, highest, and average temperature.

Design a query to retrieve the last 12 months of temperature observation data (TOBS).

Filter by the station with the highest number of observations.

Query the last 12 months of temperature observation data for this station.

Plot the results as a histogram. Output:

https://github.com/cchickowski/SQLAlchemy-Climate_Analysis/blob/bfe13535078f4711336831021299f113d5cd94f3/Station_Histogram.png
