# Pandas One Pager

## INTRO

### Reasons for it

Here is my own personal pandas one pager guide.

Even with Python and SQL experience, it can take a little while to get used to Pandas and dataframes.  I found that compiling this one pager pandas guide saved me a lot of repetitive searching and I find it useful in daily analysis work. Hope it is useful to some people learning Pandas!

### What it is not

It isn't a full Pandas guide or tutorial.

It doesn't even scratch the surface of what you can do with Pandas but it's a useful syntax guide that I refer to all the time.

## FEATURES/ CONTENTS
Here is the full contents list covered in the 'pandas-one-pager.ipynb' file:

1. Data Frame - Creation with a Dictionary

2. Date Frame - Creation from a list of lists

3. Data Frame - Creation from a list of lists - with unique Index

4. Data Frame - Creation from a CSV or Excel spreadsheet

5. Columns - Remove an unnecessary column

6. Data Types - exploring column data types

7. Sort - apply a sort to an existing dataframe

8. Index - reset index numbers after a sort

9. Index - Drop an Index from a dataframe when exporting

10. Find a specific row - based on a search string

11. Find rows based on str.contains (similar to SQL like)

12. Find rows based on filtering numbers (greater than)

13. Find a specific row - based on Index Number

14. Find specific cell data - based on Index Number

15. Find specific cell data - based on a search

16. Series - convert a series to a Dataframe or a List

17. Add a row

18. Add a row - based on previous row data

19. Update a cell - based on Index Number

20. Columns - adding a new Column

21. Columns - deleting a column

22. Columns - create a new column from a sum

23. Columns - create a new column with the APPLY() method

24. Columns - change data type - FLOAT to INTEGER

25. Columns - create a new string column based on logic in APPLY() method

26. Columns and Dates - create a year and month column from a date

27. Columns - change the names of your columns

28. Data Frame - use the APPLY() method with a LAMBDA function on an entire dataframe

29. NaN - use ISNULL() to find null values

30. NaN - use na=False to find NaN AND non-string values

31. NaN - convert missing numerical data to 0 with FILLNA()

32. Group By - counting columns

33. Group By - counting by percentage

34. Joins - Inner Join dataframes

35. Joins - Left Join  dataframes

36. Pivot - PIVOT() example

37. Pivot 2 - PIVOT() example with grouped dates sales

38. Head and Tail

39. Pivot - PIVOT_TABLE() - aggregated functions

40. Pivot table percentages - FLOAT to 2 decimal places

41. openpyxl - save dataframes to different Excel workbook sheets


======== 1. DATA FRAMES ====================

======== DATA FRAME CREATION, DATA FRAME FROM FILES ==============

Data Frame - Creation with a Dictionary

Date Frame - Creation from a list of lists

Data Frame - Creation from a list of lists - with unique Index

Data Frame - Creation from a CSV or Excel spreadsheet

============ 2. BASIC PANDAS ==========================

========== HEAD AND TAIL, REMOVE COLUMNS, EXPLORE DATA TYPES, BASIC SORTING, INDEX - DROP AND RESET =========

Head and Tail

Columns - Remove an unnecessary column

Data Types - exploring column data types

Sort - apply a sort to an existing dataframe

Index - reset index numbers after a sort

Index - Drop an Index from a dataframe when exporting

=============== 3. FIND, UPDATE AND ADD ================================

============== FIND ROWS AND CELL DATA, UPDATE CELLS, ADD ROWS =========

Find a specific row - based on a search string

Find rows based on str.contains (similar to SQL like)

Find rows based on filtering numbers (greater than)

Find a specific row - based on Index Number

Find specific cell data - based on Index Number

Find specific cell data - based on a search

  - Boolean Mask (using True or False result in another query)

Series - convert a series to a Dataframe or a List

Add a row

Add a row - based on previous row data

Update a cell - based on Index Number

================= 4. COLUMNS AND NANS =========================

================= WORK WITH COLUMNS, HANDLE NaN ===============

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

=========== 5. GROUP BY AND JOINS IN PANDAS ===================

Group By - counting columns

Group By - counting by percentage

  - Aggregate another column (such as MEAN) after Grouping a Column

Joins - Inner Join dataframes

Joins - Left Join dataframes

======= 6. PIVOT TABLES, OPENPYXL =============================================================

======= AGGREGATIONS WITH PIVOT TABLES, TRANSPOSING COLUMNS, SAVING WITH OPENPYXL =============

Pivot - PIVOT() example

Pivot 2 - PIVOT() example with grouped dates sales

Pivot - PIVOT_TABLE() - aggregated functions

Pivot table percentages - FLOAT to 2 decimal places

openpyxl - save dataframes to different Excel workbook sheets

============= 7. ADVANCED PANDAS PROFILING =========================

============= CARDINALITY, CORRELATIONS, COLUMN PROFILING ==========

Advanced Profiling

============ 8. PLOTLY ===========================================

============ VIEW AND SAVE ADVANCED GRAPHS TO HTML ===============

Histogram with Plotly

Boxplot with Plotly

Bar chart with 3 elements (using Color Continuous Scale)

Scatter chart with Plotly (with Color for 3rd element)

Cumulative Sales and Profit columns on Date Ordered Data Frame


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
