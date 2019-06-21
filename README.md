# Titanic 1

In today's challenge, we will be working with one of the most classic data sets in data science and machine learning: who survived (and who did not) on the Titanic. First, we'll read in the csv and clean the data. Then, we'll do some queries and discover some tendencies in the data.


## Release 0: Read in Data
Read in the csv file to ```titanic_1.py``` using pandas.read_csv()


## Release 1: Clean the Data
This data is pretty clean, but there are two things we want to do to make it even better. 

#### 1. Some rows contain missing values for age; delete these rows entirely. 
#### 2. Separate the current 'Name' column into 'LastName', 'FirstName', and 'Title'. You will notice some names contain nicknames or other parentheticals after them--be careful in your string slicing to make sure the rows are what you want them to be.

## Release 2: Queries
Now that you have a clean data frame, let's do some queries. Please go through all of these, as they will be helpful in the comming days.


#### 1. Get all rows from the data frame.

#### 2. All rows, but just displaying the values for 'survived' and 'sex'

#### 3. All rows where 'sex' is 'female'

#### 4. The mean of 'survived' where 'sex' is 'male'

#### 5. The mean of 'survived' where 'sex' is 'female'

#### 6. The mean of 'survived' where 'age' is less than 45

#### 7. The mean of 'survived' where 'age' is greater than 70

#### 8. The mean of 'survived' where 'sex' is 'male' and 'age' is less than 30

#### 9. The mean of 'survived' where 'sex' is 'female' and 'age' is less than 40

#### 10. The mean of 'survived' where 'Pclass' is 1

#### 11. The mean of 'survived' where 'Pclass' is 3

#### 12. The mean of 'survived' where 'sex' is 'female' and 'Pclass' is 1 and 'age' is less than 35

#### 13. The standard deviation of 'price' where 'Pclass' is 1

#### 14. The standard deviation of 'price' where 'Pclass' is 3

