# Pandas One Pager

## INTRO

### Reasons for it

Even as a fairly seasoned Python developer and having a good knowledge of SQL, I found myself having to constantly jump around various places checking Pandas syntax in the beginning.

I find it easier to have base examples in one place. I often use this guide to remind myself of syntax when performing analysis with Pandas.

Everything I have had to double check is here. There are a lot of examples on how to perform SQL/ Excel type queries and actions with Pandas.

### What its not

It isn't a full Pandas guide or tutorial.  It doesn't even scratch the surface of what you can do with Pandas but it's a useful syntax guide that I refer to all the time to perform most data anlytics tasks.

It's more of a syntax reference or a quick place to remind yourself how to do something.

## FEATURES
Here is the full contents list covered in the 'pandas-one-pager.ipynb' file:

1. Data Frame - Creation with a Dictionary
2. Date Frame - Creation from a list of lists
3. Data Frame - Creation from a list of lists - with unique Index
4. Data Frame - Creation from a CSV or Excel spreadsheet
5. Data Types - exploring column data types
6. Columns - Remove an unnecessary column
7. Sort - apply a sort to an existing dataframe
8. Index - reset index numbers after a sort
9. Index - Drop an Index from a dataframe when exporting
10. Find a specific row - based on a search string
11. Find rows based on filtering
12. Find a specific row - based on Index Number
13. Find specific cell data - based on Index Number
14. Find specific cell data - based on a search
15. Series - convert a series to Dataframe and a List
16. Add a row
17. Add a row - based on previous row data
18. Update a cell - based on Index Number
19. Columns - adding a new Column
20. Columns - Deleting a column
21. Columns - create a new column from a sum
22. Columns - create a new column with the APPLY() method
23. Columns - change data type - FLOAT to INTEGER
24. Columns - create a new string column based on logic in APPLY() method
25. Columns and Dates - create a year and month column from a date
26. Columns - change the names of your columns
27. Data Frame - use the APPLY() method with a LAMBDA function on an entire dataframe
28. NaN - convert missing numerical data to 0 with FILLNA()
29. Group By - counting columns
30. Group By - counting by percentage
31. Pivot - PIVOT() example
32. Pivot 2 - PIVOT() example with grouped dates sales
33. Head and Tail
34. Pivot - PIVOT_TABLE() - aggregated functions
35. Pivot table percentages - FLOAT to 2 decimal places
36. openpyxl - save dataframes to different Excel workbook sheets

## TOOLS
pandas
openpyxl
jupyter notebooks

## GETTING STARTED

### If you are new to Pandas or Python

- Just open up the 'pandas-one-pager.ipynb' file and start using the examples.

1. Make sure you learn Python and SQL basics before Pandas (my recommendation)
2. This pandas intro course is useful - https://www.youtube.com/watch?v=WcDaZ67TVRo&t=7270s

Pandas docs:
https://pandas.pydata.org/pandas-docs/stable/index.html

### Setting up Jupyter Notebooks

It's easier to work with Pandas inside Jupyter notebooks (although it works ok in normal .py python files). 

It's optional but it can be useful to setup Jupyter notebooks via Anaconda which has a range of useful tools you can use along with Jupyter notebooks.  You can activate your Jupyter notebooks local server via an Anaconda installation:

https://www.anaconda.com/

Check out more at the Jupyter notebook docs:

https://docs.jupyter.org/en/latest/ 
