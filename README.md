# DataScienceR


The first thing we do when we get data is calculate basic statistics like mean, median, max to get a sense of what data we are looking at. 
summary() function is only useful for numeric and logical type variables cannot compute mean, median, etc, on character and logical types. Also the functions' output is not in tidy format.

- transform each variable as a row and each type of statistics as a column with its corresponding value
   + For numbers calculate summary statistics such as min, max and mean to understand how spread out the data are around the average, how large the sample is, etc. This also helps us to quickly identify errors (e.g. negative values) and missing values. 
   + For character or text variables, find the unique values 
