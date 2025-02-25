CSV vs Parquet
CSV is a simple text format where the data are stored in rows and values seperated by comams.It is easy to read but takes more space and processes slow for large datasets.So CSV is good for small datsets.
Paraquet follows column based format and is designed for fast data processing. It makes files smaller and is much faster even while working on large datasets.But it is not human-readable and tools like pandas and Apache Arrow are used to open and processs it.So parquet has better performance for big data analysis.
