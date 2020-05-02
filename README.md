# Memory reduction function
Reduces RAM utilization by manipulating data types properly towards low size data types (from Int64>>Int8,Int16,Int32 and from Float64 to Float32 or Float 16.

Source:
https://www.kaggle.com/gemartin/load-data-reduce-memory-usage
 
Note: If you have problems with this function try to discard Float16 part, as
there might be errors because of this data type, look:
https://github.com/pandas-dev/pandas/issues/9220
