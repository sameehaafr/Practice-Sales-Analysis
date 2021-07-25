# Practice-Sales-Analysis-2021
Using Keith Galli's Dataset to answer real world business questions on 12 months of Sales Data.

Questions I answered:

- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

Libraries I used:
- os
- pandas
- matplotlib
- combinations (from itertools)
- Counter (from collections)

Steps I went through:

- Reading in 12 separate csv files (1 for each month) and merging them into 1 csv file using pandas.
- Cleaning the data. (dropping rows of Na, removing unwanted text in certain columns, convertng columns into correct data type)
- Adding columns for easier data exploration.
- Data Exploration (answering all the questions listed above)
