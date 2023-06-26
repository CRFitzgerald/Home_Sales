# Home_Sales

I created a Spark DataFrame from the housing data and called it df.

I created temporary table of the original DataFrame and called it 'housing'.

I wrote a query that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year.

![Screenshot 2023-06-25 at 11 02 22 PM](https://github.com/CRFitzgerald/Home_Sales/assets/117607189/f51e16b8-1d9c-4ce1-b064-b327b44f37a2)

I wrote a query that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms. 

![Screenshot 2023-06-25 at 11 05 31 PM](https://github.com/CRFitzgerald/Home_Sales/assets/117607189/4c0c2b6f-b8e3-494b-9d2f-f7eabd8c101d)


I wrote a query that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year built rounded to two decimal places. 

![Screenshot 2023-06-25 at 11 07 08 PM](https://github.com/CRFitzgerald/Home_Sales/assets/117607189/0fa4caee-1726-4be4-9b25-87431d11951d)


A query is written that returns the view rating for the average price for homes that are greater than or equal to $350,000, rounded to two decimal places. (The output shows the run time for this query.) 

A cache of the temporary "home_sales" table is created and validated. 

The query from step 6 is run on the cached temporary table, and the run time is computed. 

A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read.

A temporary table of the parquet data is created. 

The query from step 6 is run on the parquet temporary table, and the run time is computed. 

The "home_sales" temporary table is uncached and verified. 
