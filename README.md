# Home_Sales
Module 22

### Background:
In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.
<i>Answer the following questions using SparkSQL:</i>

* What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

* What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

* What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

* What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

<b> I guarantee my code has all of the following requirements:</b>

* A Spark DataFrame is created from the dataset.</br>
* A temporary table of the original DataFrame is created.</br>
* A query is written that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year.</br>
* A query is written that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms.</br>
* A query is written that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year built rounded to two decimal places.</br>
* A query is written that returns the view rating for the average price for homes that are greater than or equal to $350,000, rounded to two decimal places. (The output shows the run time for this query.)</br>
* A cache of the temporary "home_sales" table is created and validated.</br>
* The query from step 6 is run on the cached temporary table, and the run time is computed.</br>
* A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read.</br>
* A temporary table of the parquet data is created.</br>
* The query from step 6 is run on the parquet temporary table, and the run time is computed.</br>
* The "home_sales" temporary table is uncached and verified.
