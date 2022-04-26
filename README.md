# Pandas One Pagers

## INTRO

A set of one page help sheets for Pandas to help with Data Analysis tasks allowing you to get started quickly with the process of preparing and visualizing data.

The one pager guides are aimed to be a quick reference with simple examples.

Topics covered include removing columns, changing column names, creating new columns from calculations, finding errors, fixing errors, finding missing values, replacing missing values, looking at column distribution, correlations between columns, shaping the data - pivot tables, aggregations, grouping, filtering, joining, merging, appending tables, changing data types, advanced column profiling and also creating advanced visualizations with plotly.

### Reasons for this repo and what it is not

I created this repo because when I started out with Pandas I regularly had to check syntax.  I hope this helps others find things quickly and get going with Pandas.

These one pager guides don't constitute a full pandas guide.  However, they provide a great starting point for Data Analysis using Pandas and Plotly.

## FEATURES/ CONTENTS
Here is the full contents list covered in the 'pandas-one-pager.ipynb' file:

### 1-dataframes.ipynb

Data Frame - Creation with a Dictionary

Date Frame - Creation from a list of lists

Data Frame - Creation from a list of lists - with unique Index

Data Frame - Creation from a CSV or Excel spreadsheet

### 2-basic-pandas.ipynb

Head and Tail

Columns - Remove an unnecessary column

Data Types - exploring column data types

Sort - apply a sort to an existing dataframe

Index - reset index numbers after a sort

Index - Drop an Index from a dataframe when exporting

### 3-find-update-add.ipynb

Find a specific row - based on a search string

Find rows based on str.contains (similar to SQL like)

Find rows based on filtering numbers (greater than)

Find a specific row - based on Index Number

Find specific cell data - based on Index Number

Find index numbers - based on a search

Find specific cell data - from a list of multiple Index Numbers

  - Boolean Mask (using True or False result in another query)

Series - convert a series to a Dataframe or a List

Add a row

Add a row - based on previous row data

Update a cell - based on Index Number

### 4-columns-nans.ipynb

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

###  5-group-by-joins.ipynb

Group By - counting columns

Group By - counting by percentage

Aggregate another column (such as SUM or MEAN) after Grouping a Column

Joins - Inner Join dataframes

Joins - Left Join dataframes

### 6-pivot-tables-openpyxl

Pivot - PIVOT() example

Pivot 2 - PIVOT() example with grouped dates sales

Pivot - PIVOT_TABLE() - aggregated functions

Pivot table percentages - FLOAT to 2 decimal places

openpyxl - save dataframes to different Excel workbook sheets

### 7-pandas-profiling-report

Advanced Profiling

### 8-visualizations-with-plotly.ipynb

Histograms with Plotly

Boxplots with Plotly

Bar chart with 3 elements (using Color Continuous Scale)

Scatter chart with Plotly (with Color for 3rd element)

Cumulative Sales and Profit columns on Date Ordered Data Frame


## TOOLS

pandas

pandas_profiling

openpyxl

plotly

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
