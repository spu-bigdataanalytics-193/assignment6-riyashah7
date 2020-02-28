# ASSIGNMENT 6

Thw following tasks will be performed. 

1. Explore configuration options on SparkSession
2. Reading the data
3. Performing Tasks

    Exploring the data with Spark SQL
    
    Exploring the data with Spark DataFrame

From the list below, performed the following functions.

- Read data as RDD
- Read data as DataFrame
- Convert RDD to Spark DataFrame
- Convert Spark DataFrame to RDD
- Convert Spark DataFrame to Pandas DataFrame

## Spark SQL

To do the tasks with Spark SQL, we need to implement the tasks by writing SQL queries and executing the results with Spark SQL.

your_query = 'select * from tablename'

sparkSession.sql(your_query).show()

## Spark DataFrame

To do the tasks with Spark DataFrame, we need to use pyspark.sql.DataFrame functions like below.

data.select(...).groupBy(...)
