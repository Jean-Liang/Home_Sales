# Home_Sales
In this challenge, use knowledge of SparkSQL to determine key metrics about home sales data. Then use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Data Source from url = "https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv"

Using SparkSQL analysis below four questions:
- What is the average price for a four-bedroom house sold for each year?
- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms?
- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?
- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000?

The detailed analysis can be found in - "Home_Sales_colab.ipynb".

Runtime for dataset:
- Uncache Runtime:  0.9411220550537109 seconds
- Cached Runtime: 0.5158309936523438 seconds 
- Runtime with the parquet DataFrame: 0.7451274394989014 seconds
