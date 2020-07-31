# ETL-Project

In this project, we will be working with a list of craft beers and  a list of breweries to create an API that joins both sets of data together and allows users to search for specific attributes of each beer or brewery.

The tools we used on this project were Python, Pandas, SQLAlchemy and PostgreS.

To start, we found two data sources based in an excel files that we wanted to use:

https://www.kaggle.com/nickhould/craft-cans

# Step 1: Extract

We used Pandas to read the excel workbooks into our Jupyter notebook and created an engine to start a connection to our database.

# Step 2: Transform

We renamed some columns in both the beers dataframe and the breweries dataframe to make them easier to read and understand. 

Next, we applied a percentage format to our ABV (Alcohol by Volume) column and corrected values in the IBU (International Bitterness Units) column.

# Step 3: Load

Last, but not least, we created a connection to our database using our engine from the first step. We also grabbed our table names from the engine to send to SQL.

Finally, we sent our dataframes to SQL using Pandas.
