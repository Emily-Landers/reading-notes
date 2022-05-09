# Pandas

- Create a Series by passing a list of values, letting pandas create a default integer index.
- If you’re using IPython, tab completion for column names (as well as public attributes) is automatically enabled. 
- Selecting a single column, will yield a Series, equivalent to df.A
- Selecting via [], will slice the rows
- pandas primarily uses the value np.nan to represent missing data. It is by default not included in computations. 
- Reindexing allows you to change/add/delete the index on a specified axis. 
- Operations in general exclude missing data.
- Series is equipped with a set of string processing methods in the str attribute that make it easy to operate on each element of the array, as in the code snippet below. Note that pattern-matching in str generally uses regular expressions by default (and in some cases always uses them).
- pandas provides various facilities for easily combining together Series and DataFrame objects with various kinds of set logic for the indexes and relational algebra functionality in the case of join / merge-type operations.
- Adding a column to a DataFrame is relatively fast. However, adding a row requires a copy, and may be expensive. We recommend passing a pre-built list of records to the DataFrame constructor instead of building a DataFrame by iteratively appending records to it.
- pandas can include categorical data in a DataFrame.
- for more examples see [panda docs](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)

## References
- https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html 