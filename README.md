# Data-Manipulation-with-pandas
## 01 Transforming Data with Pandas
- **Introducing DataFrames**
- **Inspecting a DataFrame**
1. **head()** returns the first few rows (the “head” of the DataFrame).
2. **info()** shows information on each of the columns, such as the data type and number of missing values.
3. **.shape** returns the number of rows and columns of the DataFrame.
4. **.describe()** calculates a few summary statistics for each column.

- **Parts of a DataFrame**
1. **values**: A two-dimensional NumPy array of values.
2. **columns**: An index of columns: the column names.
3. **index**: An index for the rows: either row numbers or row names.

- **Sorting and subsetting**
1. Sorting rows
2. Subsetting columns
3. Subsetting row
4. Subsetting rows by categorical variables **|, .isin()**
- **Adding new columns**
## 02 Aggregating DataFrames.ipynb
- **Summary Statistics**
1. Mean and median
2. Summarizing
3. Efficient summaries
4. Cumulative statistics
5. Dropping duplicates
- **Counting**
1. Counting categorical variables
- **Grouped summary statistics**
1. Calculations with .groupby()
2. Multiple grouped summaries
- **Pivot tables**
1. Pivoting on one variable
2. Fill in missing values and sum values with pivot tables
