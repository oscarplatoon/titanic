# Titanic 1

In today's challenge, we will be working with one of the most classic data sets in data science and machine learning: the Titanic. Today, we're going to use data to figure out who survived and who did not survive on the Titanic. Maybe the conclusions you come to here will help you survive on your next cruise.

To accomplish this, we'll first read in the CSV and clean the data. Then, we'll query the data set and come to some conclusioins based off of the data.

## Release 0: Read and clean your data
Read in the CSV file to `titanic_1.py` using `pandas.read_csv()`

## Release 1: Clean the Data
There are two things that we need to do to clean the data:
1. Some rows contain missing values for age. Delete these rows entirely because they're incomplete rows.
2. Separate the current `Name` column into `LastName`, `FirstName`, and `Title`. You will notice some names contain nicknames or other parentheticals after them--be careful in your string slicing to make sure the rows are what you want them to be.

## Release 2: Queries
Now that you have clean data, let's do some Pandas queries:

1. Get all rows
2. Get all rows and display the values for `survived` and `sex`
3. Get all rows where `sex` is `female`
4. The mean of `survived` where `sex` is `male`
5. The mean of `survived` where `sex` is `female`
6. The mean of `survived` where `age` is less than 45
7. The mean of `survived` where `age` is greater than 70
8. The mean of `survived` where `sex` is `male` and `age` is less than 30
9. The mean of `survived` where `sex` is `female` and `age` is less than 40
10. The mean of `survived` where `Pclass` is 1
11. The mean of `survived` where `Pclass` is 3
12. The mean of `survived` where `sex` is `female` and `Pclass` is 1 and `age` s less than 35
13. The standard deviation of `price` where `Pclass` is 1
14. The standard deviation of `price` where `Pclass` is 3

## Release 3: Conclusions
What conclusions can you make based off the data you queried above as to who survived the Titanic?