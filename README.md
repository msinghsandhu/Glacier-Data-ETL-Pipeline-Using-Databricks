# Glacier Data ETL Pipeline Using Databricks

1. Extracted glacier data from the datahub.io website and stored it in DBFS.
2. Applied transformation operations to split the entire dataset based on their respective years.
3. Created two separate files to represent the transformed data and loaded them into DBFS.
4. Implemented a data pipeline to efficiently split the data by the century and saved them with file names indicating the beginning and end date of each century.
5. This pipeline contributes to a significant reduction in analysis time, as the dataset is organized and stored based on their corresponding years.
