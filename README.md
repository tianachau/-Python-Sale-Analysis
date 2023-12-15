# Python Sale Analysis
In this projetc, I will using sale data to walk through all data analyst jobs from data importing, data cleaning, data preparation to data analysis to give the useful insights. 

# Task 1: Data Importing
- Merging 12 months of sale data into a single file.

# Task 2: Data Cleaning & Processing
- Drop duplicates value
- Clean up NaN values from DataFrame
- Change the type of columns (to_numeric, to_datetime, astype)
- Remove unrelevant rows

# Task 3: Data Preparation
- Add month columns with datetime object method
- Add sale column (calculated column)
- Add city column

# Task 3: Data Analysis
We explore 5 high level business questions related to our data:
1. What was the best month for sales? How much was earned that month?
2. What city sold the most product?
3. What time should we display advertisemens to maximize the likelihood of customer’s buying product?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?


To answer these questions we walk through many different pandas & matplotlib methods:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
