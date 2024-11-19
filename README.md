# Athletic Sales Analysis

This repo analyzes sales data of athletic footwear based on cities in the US. Using DataFrames and various methods, we are able to determine retailers that had the greatest total sales, as well as which retailers sold the most women's athletic footwear. We also determine which day and week had the highest sales for women's athletic footwear. CSV files are used to make DataFrames for 2020 and 2021 sales data, respectively. 2020 and 2021 sales DataFrames are combined with `concat` to create a unified DataFrame by rows. Methods are used to check if any values are null, as well as general info of the DataFrames. `astype` is used to change a column's datatype to datetime. `groupby` and `pivot_table` are used various times to create data frames based on most sales by region, city, state. Values are sorted to show which cities had the most sales, as well as on what day and week were the most sales made.

<b>Sources</b></br>
Xpert for `.sum()` method when checking if any values are null</br>
05-Pandas-Data-Preparation-2/3/Activities/08-Stu_Resampling_Melting_DataFrames for `resample` method to sort women's footwear by day and week</br>
05-Pandas-Data-Preparation-2/3/Activities/04-Stu_MultiIndex_Pivoting_Car_Sales for `pivot_table method`, `sort_values`, and `rename`</br>
05-Pandas-Data-Preparation-2/2/Activities/03-Ins_GroupBy_Multiple_Columns_Aggregation for `groupby`</br>
05-Pandas-Data-Preparation-2/1/Activities/02-Stu_Concat_Country_Products for `concat` to join 2020 and 2021 DataFrames </br>
