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

Data Frame - Creation with a Dictionary
Date Frame - Creation from a list of lists
Data Frame - Creation from a list of lists - with unique Index
Data Frame - Creation from a CSV or Excel spreadsheet
Data Types - exploring column data types
Columns - Remove an unnecessary column
Sort - apply a sort to an existing dataframe
Index - reset index numbers after a sort
Index - Drop an Index from a dataframe when exporting
Find a specific row - based on a search string
Find rows based on filtering numbers (greater than)
Find rows based on str.contains (similar to SQL like)
Find a specific row - based on Index Number
Find specific cell data - based on Index Number
Find specific cell data - based on a search
Series - convert a series to Dataframe and a List
Add a row
Add a row - based on previous row data
Update a cell - based on Index Number
Columns - adding a new Column
Columns - deleting a column
Columns - create a new column from a sum
Columns - create a new column with the APPLY() method
Columns - change data type - FLOAT to INTEGER
Columns - create a new string column based on logic in APPLY() method
Columns and Dates - create a year and month column from a date
Columns - change the names of your columns
Data Frame - use the APPLY() method with a LAMBDA function on an entire dataframe
NaN - use ISNULL() to find null values
NaN - use na=False to find NaN AND non-string values
NaN - convert missing numerical data to 0 with FILLNA()
Group By - counting columns
Group By - counting by percentage
Pivot - PIVOT() example
Pivot 2 - PIVOT() example with grouped dates sales
Head and Tail
Pivot - PIVOT_TABLE() - aggregated functions
Pivot table percentages - FLOAT to 2 decimal places
openpyxl - save dataframes to different Excel workbook sheets

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
