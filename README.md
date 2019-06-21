# Titanic 1

In today's challenge, we will be working with one of the most classic data sets in data science and machine learning: who survived (and who did not) on the Titanic. First, we'll read in the csv and clean the data. Then, we'll do some queries and discover some tendencies in the data.


## Release 0: Read in Data
Read in the csv file to ```titanic_1.py``` using pandas.read_csv()


## Release 1: Clean the Data
This data is pretty clean, but there are two things we want to do to make it even better. Some rows contain missing values for age; delete these rows entirely. Secondly, separate the current 'Name' column into 'LastName', 'FirstName', and 'Title'. You will notice some names contain nicknames or other parentheticals after them--be careful in your string slicing to make sure the rows are what you want them to be.

## Release 2: Queries
Now that you have a clean data frame, let's do some queries. Pass all the tests in ```tests.py``` by correctly filling out ```titanic_queries.py```.
