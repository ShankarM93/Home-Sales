# Home-Sales

Module 22 Challenge 
 
 Understanding of SparkSQL was applied to extract important metrics from home sales data. Additionally, I utilized Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify the successful uncaching of the table.

## Questions

### The following questions were solved in code 

1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

![Uncached Data](https://github.com/ShankarM93/Home-Sales/assets/120356304/559e9848-9ba9-48fa-8bc9-3bd1ce49fac9) 
UNCACHED DATA 1.23 seconds run time. 









![Cached Data](https://github.com/ShankarM93/Home-Sales/assets/120356304/f1f67470-ed0c-4aed-b561-071e637b2843) 
CACHED DATA 2.61 seconds run time.










![Parquet data](https://github.com/ShankarM93/Home-Sales/assets/120356304/9d2d142d-a6c7-4719-babd-918030c33cc2) 
Parquet Data 0.37 seconds run time. 


