# Home_Sales

Demonstrating proficiency with SparkSQL to determine key metrics about home sales data. Temp views, partitions, caching, and uncaching were a few techniques used to complete this task.

The following questions/tasks were answered/completed:

1) Import the necessary PySpark SQL functions 

2) Read the csv data into a Spark DataFrame.

3) Create a temporary table called home_sales.

4) What is the average price for a four-bedroom house sold for each year? 

5) What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? 

6) What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? 

7) What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query.

8) Cache the temporary table home_sales. Confirm the table was cached.

9) Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

10) Partition by the "date_built" field on the formatted parquet home sales data.

11) Create a temporary table for the parquet data.

12) Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

13) Uncache the home_sales temporary table.

14) Verify that the home_sales temporary table is uncached using PySpark.

