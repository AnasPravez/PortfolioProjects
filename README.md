# SQL-project-1---automobile-data
Clean. Analyze &amp; Use the data to find top 10 most popular cars and trims for investors.


Functions used in this query are
Distinct
Trim
Cast
Length
Max length
Min length
Set
Update
Null
As
Concat
Substr

Some Steps Involved are :-
Step 1: Inspect the fuel_type column
The first thing we want to do is inspect the data in wer table so we will find out if there is any specific cleaning that needs to be done. Get an initial understanding of the data table by clicking on the PREVIEW tab that sits below the car_info toolbar.
Step 2: Inspect the length column 
The length column should contain numeric measurements of the cars. So we will check that the minimum and maximum lengths in the dataset align with the data description, which states that the lengths in this column should range from 141.1 to 208.1
Step 3: Fill in missing data
Missing values will create errors or skew wer results during analysis. We’re going to want to check wer data for null or missing values. These values might appear as a blank cell or the word null in BigQuery. 

Step 4: Identify potential errors
Once we have finished ensuring that there aren’t any missing values in were data, we’ll want to check for other potential errors. We will use SELECT DISTINCT to check what values exist in a column. we will run this query to check the num_of_cylinders column: 
Step 5: Ensure consistency
Finally, we want to check wer data for any inconsistencies that might cause errors. These inconsistencies will be tricky to spot — sometimes even something as simple as an extra space will cause a problem. We will use the TRIM function to remove all extra spaces in the drive_wheels column

