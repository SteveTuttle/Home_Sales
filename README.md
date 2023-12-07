# home-sales-sparkSQL-queries
UNC_data_bootcamp_module_22

## Challenge Description
### Background
> In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

***from the UNC Bootcamp description for this challenge***

## Deliverables
To accomplish this challenge I must complete following the instructions in a Google Colab Jupyter notebook:
1) First I will rename the `Home_Sales_starter_code.ipynb` file as `Home_Sales_SDT.ipynb`.
2) Import the necessary PySpark SQL functions for this assignment.
3) Read the `home_sales_revised.csv` data in the starter code into a Spark DataFrame.
4) Create a temporary table called `home_sales`.
5) I will then answer the following questions using SparkSQL, saving each result as subQuery:
  * What is the average price for a four-bedroom house sold for each year? _Round off your answer to two decimal places_.
  * What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? _Round off your answer to two decimal places_.
  * What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? _Round off your answer to two decimal places_.
  * What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and _round off your answer to two decimal places_.
6) Cache your temporary table `home_sales`.
7) Check if your temporary table is cached.
8) Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
9) Partition by the "date_built" field on the formatted parquet home sales data.
10) Create a temporary table for the parquet data.
11) Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
12) Uncache the `home_sales` temporary table.
13) Verify that the `home_sales` temporary table is uncached using PySpark.
14) Download your `Home_Sales.ipynb` file and upload it into your "Home_Sales" GitHub repository.

**Special Note:**
There was a vast improvement in runtime after the temporary table was cached, however the improvement after the partition was only very slight.

## Resources
### Bootcamp References
[Module 22 Instructions](https://bootcampspot.instructure.com/courses/3285/assignments/52255?module_item_id=937660)

Module 22 class activities

starter_code
* Home_Sales_starter_code.ipynb
* Home_Sales_starter_code_colab.ipynb

***Special Thanks:***
* Jamie Miller
* Mounika Mamindla
* Lisa Shemanciik

### External References
* [PySpark documentation](https://spark.apache.org/docs/latest/api/python/)
* [Google](https://www.google.com)
* [YouTube](https://www.youtube.com)
