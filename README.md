# ASSIGNMENT 6

Thw following tasks will be performed. 

1. Explore configuration options on SparkSession
2. Reading the data
3. Performing Tasks

    Exploring the data with Spark SQL
    
    Exploring the data with Spark DataFrame
    
### 1. Exlploring configuration options on SparkSession

Exploring atleast 5 configuration options for SparkSession. Sample as below: 

SparkSession.builder.config("spark.some.config.option", "some-value")

### 2. For Reading the data

Performed the following operations.

- Read data as RDD
- Read data as DataFrame
- Convert RDD to Spark DataFrame
- Convert Spark DataFrame to RDD
- Convert Spark DataFrame to Pandas DataFrame

### 3. Tasks

From following tasks were performed using two methods:

> using pyspark.sql.dataframe functions

> using SQL queries 

- Select first 10 rows of dataset.
- Show the schema of of the dataset.
- Group by and get max, min, count of a column in the dataset.
- Filter your dataset by some conditions based on your column.
- Apply group by with having clause.
- Apply order by.
- Select distinct records by a column.
- Transform the data type of columns from int to string/ string to integer.

## Spark SQL

To do the tasks with Spark SQL, we need to implement the tasks by writing SQL queries and executing the results with Spark SQL.

your_query = 'select * from tablename'

sparkSession.sql(your_query).show()

## Spark DataFrame

To do the tasks with Spark DataFrame, we need to use pyspark.sql.DataFrame functions like below.

data.select(...).groupBy(...)
