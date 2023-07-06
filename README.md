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
## 02 Aggregating DataFrames
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

## 03 Slicing and Indexing DataFrames
- **Explicit indexess**
1. Setting and removing indexes
2. Subsetting with .loc[]
3. Setting multi-level indexes
4. Sorting by index values
- **Slicing and subsetting with .loc and .iloc**
1. Slicing index values
2. Slicing in both directions
3. Slicing time series
4. Subsetting by row/column number
- **Working with pivot tables**
1. Pivot temperature by city and year
2. Subsetting pivot tables
3. Calculating on a pivot table

## 04 Creating and Visualizing DataFrames
- **Visualizing your data**
1. Which avocado size is most popular?
2. Changes in sales over time
3. Avocado supply and demand
4. Price of conventional vs. organic avocados
- **Missing values**
1. Finding missing values
2. Removing missing values
3. Replacing missing values
- **Creating DataFrames**
1. List of dictionaries
2. Dictionary of lists
- **Reading and writing CSVs**
1. CSV to DataFrame
2. DataFrame to CSV
