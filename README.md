# SQLAlchemy-Climate_Analysis

## Climate Analysis and Exploration
To begin, use Python and SQLAlchemy to do basic climate analysis and data exploration of your climate database. All of the following analysis should be completed using SQLAlchemy ORM queries, Pandas, and Matplotlib.

Start by finding the most recent date in the data set.

Using this date, retrieve the last 12 months of precipitation data by querying the 12 preceding months of data. Note you do not pass in the date as a variable to your query.

Select only the date and prcp values.

Load the query results into a Pandas DataFrame and set the index to the date column.

Sort the DataFrame values by date.

Plot the results using the DataFrame plot method. Output:

! (https://github.com/cchickowski/SQLAlchemy-Climate_Analysis/blob/b4c649aaf447b3c43b2fb3448dcb1965cf62ae57/Precipitation_Analysis.png)

